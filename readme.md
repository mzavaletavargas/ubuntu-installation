# Dell XPS 13

#Install Terminator

sudo apt-get install terminator

# Gihub

#Install Github

sudo apt install git-all

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

# Installing Simple Screen Recorder

If you are using Ubuntu 17.04 or newer, SimpleScreenRecorder can be found in the official repositories. You can install it with:
~~~~
sudo apt-get update
sudo apt-get install simplescreenrecorder
# if you want to record 32-bit OpenGL applications on a 64-bit system:
sudo apt-get install simplescreenrecorder-lib:i386
You should copy-paste these commands to a terminal line by line rather than all at once, otherwise it won't work.
~~~~
16.10 or older version, add ppa
~~~~
sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
sudo apt-get update
sudo apt-get install simplescreenrecorder
# if you want to record 32-bit OpenGL applications on a 64-bit system:
sudo apt-get install simplescreenrecorder-lib:i386
~~~~
