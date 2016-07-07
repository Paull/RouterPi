# RouterPi
a router made with Raspberry Pi which helps you to explore free.

# Instruction
* comparing to install softwares/apps for proxying, a well configured router would help you free the device up without install anything. It's very usefull for the devices that need internet but can't setup your own proxy on them.(Like Chromecast/Game Console)

# Install Steps
1. you need a Raspberry Pi (any version but at least one ethernet).
1. download and flash a fresh RASPBIAN JESSIE LITE to your SD/TF card.
1. eject the SD/TF card and re-inject it. (or any commands remount it?)
1. copy the scripts folder to the home directory for the user pi. (Like: cp -r scripts/ /media/somebody/123e4567-e89b-12d3-a456/home/pi/)
1. boot your Pi up and connect into the console/ssh.
1. run "sudo raspi-config" and do some nesecery changes yourself.
1. run the "INSTALL.sh" script and wait for it's over.

# Issues
feel free to open an issue on github if anything stoping you from finishing the installation.
