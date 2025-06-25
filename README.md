# picopowered
A simple microcontroller built around the RP2040.

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

PCBA - 90$ (All components are SMD to save space and as per RP2040 Spec.) 

For parts specific BOM, check picopowered.csv in /Production/