# LogiOps configuration for MX Master 3S

I use Mx Master 3s  mouse model in Windows 11 and Linux (Ubuntu 22.04 LTS) and I wanted to keep most of the behaviors I'm used too. 


Tested:
- Scroll up/down fast (property name is hiresscroll).
- Scroll left/right fast (property name is hiresscroll).
- Back button (lateral).
- Next button (lateral).
Not tested:
- Gestures.


## Setup

1. Install:

   ```shell
   sudo apt install logiops
   ```
1. Copy the configuration file or the bits you fancy (you need to edit _/etc/logid.cfg_ using `sudo`)
1. Restart `logid` service:

   ```shell
   sudo systemctl restart logid
   ```
1. Check service status:

   ```shell
   sudo systemctl status logid
   ```


## References

- https://github.com/PixlOne/logiops/tree/main
- https://danishshakeel.me/configure-logitech-mx-master-3-on-linux-logiops/
- https://github.com/torvalds/linux/blob/master/include/uapi/linux/input-event-codes.h
