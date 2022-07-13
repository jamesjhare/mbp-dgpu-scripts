# mbp-dgpu-scripts
Scripts to enable/disable the discrete GPU in older MacBook Pro models in Linux.


This is tested on Ubuntu 22.04 with a MBP 8,3 but should work on other versions of Linux (as long as using Grub as your bootloader). 

Copy disable_dgpu and enable_dgpu to your PATH and mark as executable

Copy 10_linux.dgpu_disabled and 10_linux.dgpu_enabled to /etc/grub.d

Copy grub.dgpu_disabled and grub.dgpu_enabled to /etc/default

The scripts must be run as a user with permission to alter boot entries and configuration files in /etc -- typically root and as written checks that root is running the script.
