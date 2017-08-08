# Dell XPS 13

#Install Terminator

sudo apt-get install terminator

# Trackpad

~~~~
sudo apt-get install xserver-xorg-input-libinput

edit

/usr/share/X11/xorg.conf.d/90-libinput.conf

edit

Section "InputClass"
        Identifier "libinput touchpad catchall"
        MatchIsTouchpad "on"
        MatchDevicePath "/dev/input/event*"
        Driver "libinput"
        Option "Tapping" "True"
        Option "PalmDetection" "True"
        Option "TappingDragLock" "True"
EndSection
~~~~

# install pop corn time
https://github.com/popcorn-official/popcorn-desktop
# install nodejs 

~~~~
https://www.rosehosting.com/blog/install-npm-on-ubuntu-16-04/
~~~~

# Install Anaconda

~~~~
bash file.sh
source ~/.bashrc // after reopen a terminal

~~~~
# Resize images in ubuntu

~~~~
https://askubuntu.com/questions/1164/how-to-easily-resize-images
sudo apt-get install nautilus-image-converter
nautilus -q
~~~~
