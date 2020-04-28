# FreeRTOS Raspberry Pi3B+  (BCM2837B0)
## Knowledge
BCM2837 = BCM2837A0 = BCM2837B0 with same hardware but only different cpu frequency.
## Building
### Windows
Get the compiler "gcc-arm-none-eabi-4_7-2013q3-20130916-win32.exe" by downloading it from [google drive](https://drive.google.com/open?id=1-0Cy-zFqS9TJBSg7oknKmI__W69GrhNu) given below and install it, when it asks environment variable, just skip it.

Run this bat "/path/to/your/install_path/GNU Tools ARM Embedded/4.7 2013q3/bin/gccvar.bat", it will automatically and temporary set your environment variable in building, maybe you can make a shortcut to desktop that is easy for you to make use of it.

Move to the folder where you cloned this repository at, eg. "D:/Code/Raspberry_Pi3_FreeRTOS".

run following command
```
cd D:/Code/Raspberry_Pi3_FreeRTOS
make
```

## Demo
This FreeRTOS demo creates 2 Tasks, one controls LED & other prints text.

Connect to USB-UART to see task status 

## Kernel Installation Guide
You can first install raspberian into your SD card and copy "kernel7.img" we just built to your SD card.

Works only on Raspberry Pi3B+ or BCM2837 ....
