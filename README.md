# ATmega328PB Arduino Nano Clone config incl. Bootloader
The bootloader is a modified version of Optiboot (https://github.com/Optiboot/optiboot).

## How to install
Add the following URL to the Arduino Board Manager (**File > Preferences > Additional Boards Manager URLs**)
```
https://github.com/dprinz4/ATmega328PB-Nano-Clone-with-Bootloader/raw/master/package_m328pb_index.json
```
Then search in the Board Manager for **ATmega328PB** and click install.

If this fails, you might download the zip file and unzip it to:
```
C:\Users\<Your Username>\AppData\Local\Arduino\packages\ATmega328PB-with-Bootloader\hardware
```

## How to burn the Bootloader
I recommend following this instruction: https://sysexit.wordpress.com/2013/02/07/burning-a-bootloader-to-an-arduino-nano-using-another-arduino/

Simply select "ATmega328P" as board, instead of "Arduino Nano w/Atmega 328 again"
