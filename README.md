# Arduino Matrix clock
Arduino matrix clock based on max7219 8*8 matrix module & ds3231 clock module
## Parts List -
* Arduino uno/nano/pro mini
* Max7219 8*8 matrix module (4 pcs)
* DS3231 Clock module
## Clock Features
* Time
* Calender
* Day of week
* Room Temperature in both celsius and fahrenheit
* Message
# Notes :
* If you have wrong display orientation or different matrix module type then try changing the code with one of these module types GENERIC_HW/FC16_HW/PAROLA_HW/ICSTATION_HW.

#define HARDWARE_TYPE MD_MAX72XX::FC16_HW // Module type FC16_HW
## Pinout :
### Arduino   &nbsp; MAX7219  &nbsp;     DS3231
- 13->   &nbsp;   &nbsp;  &nbsp;   CSK
- 10->      &nbsp;   &nbsp; &nbsp; CS
- 12->        &nbsp;  &nbsp; &nbsp; DATA
- A4->          &nbsp; &nbsp;   &nbsp;   &nbsp; &nbsp;   &nbsp;     &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp;   &nbsp;   SDA
- A5->            &nbsp; &nbsp;   &nbsp;   &nbsp; &nbsp;   &nbsp;      &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp;   &nbsp;  SCL
- VCC->      &nbsp; &nbsp;   &nbsp; VCC   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp;   &nbsp; VCC
- GND->        &nbsp; &nbsp;   &nbsp;    GND  &nbsp; &nbsp;  &nbsp; &nbsp;   &nbsp; &nbsp;  &nbsp; &nbsp;   &nbsp;     GND
