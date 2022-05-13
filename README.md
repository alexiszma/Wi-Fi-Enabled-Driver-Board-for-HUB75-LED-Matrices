# ESP32 Based HUB75 Matrix Driver
*Note: This project is a work in progress. Stay tuned!* 
## Table of Contents
  * [Ethos](https://github.com/alexiszma/Wi-Fi-Enabled-Driver-Board-for-HUB75-LED-Matrices/blob/main/README.md#ethos)
  * [General Information](https://github.com/alexiszma/Wi-Fi-Enabled-Driver-Board-for-HUB75-LED-Matrices/edit/main/README.md#general-information)
    * [Programming and Sofrware]()
    * [Power]()
    * [Misc.]()
  * [Acknowledgments]()



---
## Ethos
The main goal of this project is to design an easy-to-use method of interfacing with widely-available [HUB75 RGB LED matrix panels](https://github.com/pixelmatix/SmartMatrix/wiki/HUB75-Panels). All one will have to do is to snap the board onto place, program the MCU to one’s desire, and voila! The emphasis on the ease of use comes from the fact that it would result in user-friendly boards if I were to decide to make this a commercially available product. Nonetheless, all the files pertaining to this project will be open sourced! :)

---
## General Information 

### Programming and Software
This board is designed to be programmed in the [Arduino IDE](https://www.arduino.cc/en/software). The board features a USB-C connector that is exclusively used to program the MCU (i.e. the matrix will not be powered on when only USB-C is connected). The ESP32 also supports over-the-air programming although this has not been tested with this specific setup yet.

### Power
The board features a 5V 5.5mm barrel-style jack that will be used to power both the MCU and the panel. Due to the high current draw of a HUB75 RGB matrix panel, an external DC power supply of 4 Amps (or more) is recommended. 

### Misc.
In addition to Wi-Fi, the ESP32 MCU features Bluetooth connectivity. The board will also feature 2 capacitive touch pads intended for use to control brightness (although ultimately they can be used for anything). 

---
## Acknowledgments 
Special thanks to Brian Lough and Russ Schaller for advising me during different stages of this project.
