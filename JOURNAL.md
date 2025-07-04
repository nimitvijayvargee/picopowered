---
title: "picopowered"
author: "nimit vijayvargee"
description: "Versatile dev board for a pico replacement!"
created_at: "2025-06-17"
---
# Day 1 - 17th June
Time spent: 2 Hours <br>
Researched RP2040 Hardware documentation and the Pico Datasheets for reference. Began laying out the schematic on KiCad.
I also used my mom's work printer to print the RP2040 Hardawre docs to read through. I selected a few of the specific components to use
like the specific 12MHz crystal and the QSPI Flash Chip. 
![image](https://github.com/user-attachments/assets/4788266f-945b-403b-9a69-79c97bb81893)
![image](https://github.com/user-attachments/assets/030791db-973c-4bcb-bfe3-b2bbb99a299e)

# Day 2 - 18th June
Time spent: 1 Hour <br>
Completed the Powerchain and QSPI Flash chip. Did a bit of digging on the footprint for the Abracon 12MHz crystal. Did a bit or organizing on
my schematics to make them more readable than even the Pico docs.
![image](https://github.com/user-attachments/assets/ed03c018-c5ab-44e9-90f7-2d7493ef7416)

# Day 3 - 19th June
Time spent: 2 Hours <br>
Took a printout of the original Pico 1 to compare my designs, also added the crystals and GPIO headers! Almost ready to begin the routing.
![image](https://github.com/user-attachments/assets/1ac737a1-be29-4112-a92f-759121977a1e)
![image](https://github.com/user-attachments/assets/2dfb95bd-b02e-407c-ba8e-f8437bc99f23)
![image](https://github.com/user-attachments/assets/fc22801d-a093-4131-a9eb-d1c7d402ecd4)

# Day 4 - 20th June
Time spent: 2 Hours <br>
Finished up the schematic and made it look pretty! Set up footprints and added the components to the PCB. Also fixed some values in the capacitors.
The component layouts took some time.
![image](https://github.com/user-attachments/assets/f8a0d9e6-298a-4e7d-b069-db887623f9f3)
![image](https://github.com/user-attachments/assets/48af159b-32fd-488f-afff-4ba94011ab56)

Neet to take some measurements before I can actually start tracing.

# Day 5 - 21st June
Time spent: 4 Hours <br>
Experimented with a lot of routing methods and component placements. Fixed footprints to smaller version (5050 LED -> 2020 LED, smaller caps, etc.).
Researched on a lot of electrical requirements to make a ground plane work. Did a lot of routing, deletion and more routing. Power spike caused Kicad to 
delete the saved work causing me to restart the PCB the following day.

# Day 6 - 22nd June
Time spent: 5 Hours <br>
Cotinued difference combinations of routing and component placements. However, a power spike caused me to lose the progress over the previous day. Schematic was autosaved and recovered so i was able to replace all components, reroute and prepare for fabrication. Started designing silkscreen art!
![image](https://github.com/user-attachments/assets/ad5ae6d4-4b05-42da-bc17-61fb6d31e3a5)
![image](https://github.com/user-attachments/assets/d0d4abeb-978a-43b5-b35a-7f0e68ca9849)
![image](https://github.com/user-attachments/assets/3abb054e-def9-4c1e-ba7b-07c0d7a67670)

# Day 7 - 23rd June
Time spent: 2 Hours <br>
Finished Silkscreen with cool arrows and a logo! Prepared some files for production. Added some labels to the Powerchain, Crystal clock and the GPIO pin numbers on the neopixel and user button.

# Day 8 - 25th June
Time spent: 1 Hour <br>
Prepared BOM and Gerbers for JLC and readied submission for highway :D


