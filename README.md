
# simple-UPDI-programmer (jtag2updi)

An Arduino UPDI programmer, based on [ElTangas jtag2updi](https://github.com/ElTangas/jtag2updi).  
Configured to be uploaded straight from PlatformIO, instead of Arduino IDE.  
Simply change the target board in `platformio.ini`.  

    board = nanoatmega328new
  
## Hardware
Guide on how to build your own programmer: [Link](https://daumemo.com/diy-updi-usb-programmer-which-can-be-made-with-cheap-hardware/)  

For anyone interested, I've added two SPDT switches: one for toggling VCC between 3.3V and 5V,   
and another to bypass the 4.7K resistor, which I've found sometimes helps to establish connection.  
  
> ***J2** has to be ***OPEN*** when programming the programmer itself*.  


![simple_schematic.png](/simple_schematic.PNG)

  
