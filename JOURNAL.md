---
title: "nfc card"
github: "https://github.com/SunnyBoiX/nfc-card"
description: "I'm making an NFC card because it seems like the easiest thing for a beginner like me. "
created_at: "2026-10-24"
total_time: "1h 30m"
---

# October 24, 2026: Finished NFC schematic design

## October 24, 2026: Schematic Design & Wiring

### Initial Design & Wiring
![](https://fabricate.hackclub-assets.com/bfcf4c48914c3f70f8da5d3257f76cd45b0fa9e9d9459c8a62b6998a8f029f30/image-png/image.png)


I built the schematic for my NFC card in EasyEDA to harvest power from a phone tap and light up an LED. The design uses an NXP NT3H2111 chip for NFC communication and power harvesting, a PCB antenna to capture the phone's signal, a 220nF capacitor to smooth out the power, and an LED with a 47Ω resistor that turns on when power is detected. After verifying that the TSSOP-8 chip package uses standard pins without needing an exposed pad, the schematic is fully complete and ready for PCB layout.

**Total time spent: 30m**

# October 24, 2026: Finished PCB Layout & Antenna Routing

## October 24, 2026: PCB Layout And Routing

## PCB LAYOUT AND ROUTING
![](https://fabricate.hackclub-assets.com/112d0aad9ddaea284064e44877b07e7ab921cc8f983ca5882ec0b5fbeaf301d9/image-png/%7BAC00929F-BD4A-432B-828D-CE299FBCE7B7%7D.png)
## 3D VIEW
![](https://fabricate.hackclub-assets.com/465f5d391f5342d9144805ccfad60e877c407e1d4d5b38c8b7cd51fc5c832f2d/image-png/%7B26936CB2-6217-457F-8459-7090FEBFBC10%7D.png)


For this part of the project, the board outline was defined to an 88.9mm × 50.8mm rectangle with 4mm rounded corners to make sure it was like the size of a credit card and can fit into my wallet. The IC (NXP NT3H2111), smoothing capacitor, resistor, and LED were positioned inside the outline directly adjacent to the PCB antenna loop on the top copper layer. Copper track routing was completed to connect the NFC tag controller, energy-harvesting circuitry, and LED indicator, leaving the board layout fully finalized.

**Total time spent: 1h**
