### Repository Content
* **/hardware** : Schematic files (.pdf) some of older version included Eagle design files (.sch and .brd)
* **/production** : gerber file for pcb manufacturing

You can purchase this product from [![Generic badge](https://img.shields.io/badge/Indonesia-Tokopedia-<COLOR>.svg)](https://www.tokopedia.com/geraicerdas/esp32-cam-programmer-ai-thinker-esp32-s-camera-5v-serial-converter-module-only) 
[![Generic badge](https://img.shields.io/badge/Worldwide-Tindie-red.svg)](https://www.tindie.com/products/geraicerdas/esp32-cam-programmer/)

# ESP32-Cam-Programmer
This is external programming for ESP32-Cam that you can simple attach it for easy upload your code to ESP32-Cam. Keep the slide switch at 3.3V so it is not harmful for your ESP32-Cam. ESP32-Cam programmer also have a breakout pins that makes it easier for you to connect the I/O pins of the ESP32-Cam to other circuits (no need breadboard). Not only for ESP32-Cam, you can use this board to program another MCU's like Arduino Pro mini that need USB to Serial Converter

The latest version have several changes :
- Added a 3V3 Voltage Regulator
- Added voltage selector switch (5V or 3.3V compatible)
- Compatible with both older or newer ESP32-Cam
- changes PCB shape and color

<p float="left">
<img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2022/1/21/1f761d49-8080-4828-abe8-a921d91b518c.jpg" width=400 /> 
<img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2022/1/21/b6bc6f3f-a4ee-471e-a235-99eecc138935.jpg" width=400 />
<img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2022/1/21/ced4d599-39a8-4006-b4e8-bedb4a3bbb8b.jpg" width=805 /> 
</p>


If you want to make your self, just download the gerber file in production folder. Send it to your fav pcb manufacturer. And dont forget to get the Bill of materials :
|Qty | Part Name | Parts | MPN |
| ------------- |:-------------|:-------------| -----:|
| 2 | Female Header 8P 2.54mm pitch | J2, J3 | |
| 2 | Male Header 8P 2.54mm pitch | J5 | |
| 1 | USB type C Connector 16P | J4 | U262-161N-4BVC11 |
| 1 | CH340G/CH340C | U1 | CH340G |
| 1 | SMD Resonator 12MHz CSTCE | X1 | CSTCE12M0G15C99-R0 |
| 1 | AP2112K-3.3TRG1 | U2 | AP2112K-3.3TRG1 |
| 1 | Chip Resistor 0 0805 | R10, R11 | 0805W8F0000T5E |
| 3 | Chip Resistor 1K 0603 | R4, R6, R7 | 0603WAF1001T5E |
| 3 | Chip Resistor 10K 0603 | R1, R2, R3 | 0603WAF1002T5E |
| 2 | Chip Resistor 4K7 0603 | R8, R9 | 0603WAF4701T5E |
| 5 | Chip Capacitor 100nF 0603 | C3, C5, C6, C8, C21 | CL10B104KB8NNNC |
| 3 | Chip Capacitor 10uF 0603 | C2, C4, C7 | CL10A106KP8NNNC |
| 1 | N-Channel MOSFET AO3400 | Q1 | AO3400 |
| 2 | Transistor S8050 | Q2, Q3 | S8050 |
| 2 | Slide Switch AYZ0202W | SW | SS-3390S-L2 |
| 2 | Push Button YD3414 | S1, S2 | TS-1186U-B-A |
| 2 | SMD LED 0805 Red | RX, TX | |
| 1 | SMD LED 0805 Green | PWR | |
| 1 | Schottky Diode 1N5819HW | D1 | 1N5819WS |

Below is the first version of ESP32-Cam Programmer. We keep this for your references.

<p float="left">
<img src="https://ecs7.tokopedia.net/img/cache/900/VqbcmM/2021/1/20/0cee6626-4e0b-4d04-bf8a-30e3e52d6e20.jpg" width=400 /> 
<img src="https://ecs7.tokopedia.net/img/cache/900/VqbcmM/2021/1/20/560549d7-d495-413d-a784-35417a159ad9.jpg" width=400 /> 
<img src="https://ecs7.tokopedia.net/img/cache/900/VqbcmM/2021/1/20/1244e61b-8b12-4fa8-89a3-6300f83756bb.jpg" width=805 />
</p>

## License
*We invests time and resources providing this open-source hardware, please support us by purchasing our products.*

*Designed by **[Insan Sains](https://www.youtube.com/nextinnovator)** for **[Gerai Cerdas](https://geraicerdas.com)**, with contributions from the open source community. Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional information.*
