# Dasai-Mochi
Final product:
<img width="598" height="522" alt="Screenshot 2026-06-26 at 12 31 29" src="https://github.com/user-attachments/assets/2f5a6fb4-a490-4037-a295-f9bdf456bc5f" />
<img width="621" height="538" alt="Screenshot 2026-06-26 at 12 31 52" src="https://github.com/user-attachments/assets/a9c760c7-d9bb-489d-92aa-d5fb966b817d" />


In this project I will be making a dasai mochi.
I wanted to built it as I actually really want to have a pet, but as I am currently living in dormitory, it is not allowed. 
So, I wanted to make my own robot pet to lighten up my mood or to accompany me here.

The final design

<img width="586" height="567" alt="Screenshot 2026-03-27 at 21 20 41" src="https://github.com/user-attachments/assets/5d3010de-a6ec-42dd-a327-926f717850e2" />


## Key Features
* **ESP32C3** is the main microcontroller 
* **OLED display 128 x 64 px** for displaying the faces and current state of emotion
* **Type-c charging battery module** to give me an alternative power supply method (can be from the type c cable or the batery) 
* **TTP223 Touch Button Module** The touch sensor for petting
* **Buzzer loud bottom speaker** to make cute sounds
* **On-Off Mini Slide Switch 3pin 1P2T** to regulate the power supply from battery
* **MAX98357A Audio amplifier** to take digital audio data directly from a microcontroller and amplify it to drive a speaker
* **4 Heat insert** to connect the top and bottom part of the case

## Component connection
The connection is designed in KiCad. 
Here's the schematic diagram of my Dasai Mochi
<img width="705" height="481" alt="Screenshot 2026-02-04 at 18 11 58" src="https://github.com/user-attachments/assets/b2ddcee8-530d-4251-bc92-5b69694a7a09" />

I don't make it as a PCB in this project as I think it is unecessary and can cut cost
## 3D Design
I make this design in Fusion360 

Bottom Part


<img width="618" height="497" alt="Screenshot 2026-03-27 at 21 22 00" src="https://github.com/user-attachments/assets/bf9c09d9-f9d1-4c78-8a99-7ebc2b3a0cbf" />

Top Part

<img width="411" height="371" alt="Screenshot 2026-03-27 at 21 22 31" src="https://github.com/user-attachments/assets/32c2674e-7bdb-4b9c-969a-2be28cefe7f5" />


## BOM
| Item                                                     | Quantity | Unit Price (IDR) | Total Price (IDR) | Link                                                                                                                                                                           |
| -------------------------------------------------------- | -------: | ---------------: | ----------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USB Type-C Mini Charger Module (5V / 4.2V / 3.7V, 18650) |        1 |         Rp12.000 |          Rp12.000 | [Link](https://www.tokopedia.com/awallaptop/usb-type-c-mini-modul-charge-charger-type-c-5v-4-2v-3-7v-18650-lithium)                                                            |
| Rechargeable Battery CR123 / 16340 3.7V 1300mAh          |        2 |          Rp9.000 |          Rp18.000 | [Link](https://www.tokopedia.com/sehat-sejahtera-makmur/ssm-baterai-cas-cr123-batu-batrai-lc-16340-battery-3-7v-1300-mah-batere-rechargeable-1731313326437205378)              |
| Buzzer Loud Speaker (Samsung type)                       |        1 |          Rp5.900 |           Rp5.900 | [Link](https://www.tokopedia.com/a1accessories/buzzer-loud-speaker-bawah-samsung-a10-a20-a30-a50-m10)                                                                          |
| OLED 1.3" 128×64 SPI Display (4-Pin)                     |        1 |         Rp48.500 |          Rp48.500 | [Link](https://www.tokopedia.com/alfaelectro/oled-1-3-inch-128x64-spi-lcd-led-display-4pin-1731738037238990352)                                                                |
| Switch 3-Pin                                             |       10 |            Rp500 |           Rp5.000 | [Link](https://www.tokopedia.com/arduinonano/ss12d00-g4-toggle-switch-saklar-on-off-2-position-3p-slide-geser-3pin)                                                            |
| TTP223 Touch Sensor                                      |        2 |          Rp2.500 |           Rp5.000 | [Link](https://www.tokopedia.com/khurs-iot/ttp223-modul-tombol-sentuh-touch-sensor-capacitive-switch-board)                                                                    |
| Jumper Wire Dupont 20cm (Male-Male)                      |        1 |          Rp5.000 |           Rp5.000 | [Link](https://www.tokopedia.com/arduinonano/kabel-jumper-cable-dupont-pelangi-20cm-header-cable-pin-rainbow-20-cm-male-male)                                                  |
| Brass Heat Insert (30 pcs)                               |        1 |         Rp53.000 |          Rp53.000 | [Link](https://www.tokopedia.com/indocart/3d-printer-tools-compatible-brass-heat-insert-nuts-double-twill-knurled-injection-copper-thread-inserts-x-30pcs-1731656093817144863) |
| ESP32-C3 Super Mini                                      |        1 |         Rp38.900 |          Rp38.900 | [Link](https://www.tokopedia.com/alfaelectro/esp32-c3-super-mini-wifi-wireless-bluetooth-esp32-c3)                                                                             |
| MAX98357A I2S 3W Class-D Amplifier                       |        1 |         Rp55.000 |          Rp55.000 | [Link](https://www.tokopedia.com/alfaelectro/max98357-i2s-3w-class-d-amplifier-dac-decoder-module-max98357a-1733864629661500944)                                               |
| Self-Tapping Screw M3×10                                 |        1 |            Rp100 |           Rp1.000 | [Link](https://www.tokopedia.com/centi-store/self-tapping-screw-sekrup-skrup-countersunk-fh-m3-m4-m5-m6-flat-head-counter-sunk-8mm-16mm-20mm-50mm-1731498892436342400)         |
| **TOTAL COMPONENTS**                                     |          |                  |     **Rp247.300** |                                                                                                                                                                                |


## Extra stuff
Thankyou for KiCad, Fusion360, and Blueprint Hackclub to make this project possible

