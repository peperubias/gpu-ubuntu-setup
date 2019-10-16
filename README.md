# gpu-ubuntu-setup
in case I have to install it again

# Steps
1. ```sudo apt-get update```
2. Follow the steps [here](https://www.linuxbabe.com/ubuntu/install-nvidia-driver-ubuntu-18-04)
... 
After many back and forths, found the exact [bug](https://askubuntu.com/questions/1043398/broken-desktop-background-on-ubuntu-18-04-under-gnome-after-waking-up-from-suspe)
3. Switching from idle to deep suspend mode improved the background from [corrupted to just black.](https://askubuntu.com/questions/1029474/ubuntu-18-04-dell-xps13-9370-no-longer-suspends-on-lid-close/1036122#1036122)
4. Other relevant threads [here](https://gitlab.gnome.org/GNOME/gnome-shell/issues/1084) and [here](https://bugs.launchpad.net/ubuntu/+source/mutter/+bug/1809407)
