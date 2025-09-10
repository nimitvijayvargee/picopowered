# picopowered
A simple microcontroller built around the RP2040.

# Changelog (V3)
- Redesigned board layout
- Doubled headers
- Dip switches and SD card slot connected to GP13-15 and GP16-19+29 respectively
- Better power system and circuit design

# Changelog (V2)
- Replaced 2020 Neopixel with more available 5050 footprint.
- Fixed seperation between 1v1 and 3v3 power planes.
- Better positioning and tracing of the components to improve overall signal integrity.
- Added a regular LED to keep it somewhat compatible with regular Pico SDK Code.
- Modified USB C port to be THT Mounted rather than completely SMD.
- Moved GPIO 29 from VSYS Sense to an exposed pad on the bottom side of the PCB.


# Featureset
| **Stat**         | **Raspberry Pi Pico 1** | **Picopowered V1-RP2040** |
|------------------|-------------------------|---------------------------|
| Flash            | 2MB                     | 16MB                      |
| Reset Button     | No                      | Yes                       |
| LED              | Yes (1 Color)           | Yes (RGB Neopixel)        |
| User GPIO Button | No                      | Yes                       |
| USB Type         | Micro-B                 | C                         |

# Disadvantages
- Linear regulator requuires minimum of 3.3 Volts, unlike Pico's buck boost converter which can be powered by 1.8 Volts.
- No ADC_VREF (connected to GND instead) because the power by linear regulator is filtered already.
- No Power Mode (GPIO23).

Most of the disadvantages occur only due to the Pico's superior power supply system, but the system on the PicoPowered board is more filtered and smooth.

# BOM
| **Part**         | **Cost (USD)**          |
|------------------|-------------------------|
| PCB + Assembly   | 120                     |
| Solder Wire      | 3                       |
| Headers          | 3                       |



For parts specific BOM, check picopowered.csv in /Production/

# Gallery
## V3 (Latest)
![alt text](/img/v3.png)
## V2
![alt text](/img/v2.png)
## V1
![image](/img/v1.png)

