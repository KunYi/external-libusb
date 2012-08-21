external-libusb
===============
libusb v1.0.9 for Android

ref.
libusb projects ( http://www.libusb.org/)

http://grokbase.com/p/gg/android-building/123vn6bfg5/porting-libusb-to-android

tips:
insert the below into on-boot session of init.rc

# usbfs
       mkdir /proc/bus/usb 0771
       mount usbfs none /proc/bus/usb -o devmode=0666