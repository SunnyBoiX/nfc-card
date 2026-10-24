---
title: "NFC CARD"
github: "https://github.com/SunnyBoiX/nfc-card"
description: "NFC Card"
created_at: "2026-10-24"
total_time: "0.5h"
---

# JOURNAL - PROGRESS OF NFC CARD

## October 24, 2026: Schematic Design & Wiring

### Initial Design & Wiring
<img width="1200" alt="NFC Schematic" src="https://fabricate.hackclub-assets.com/0f4929be7d4b3a7455bd3c734a68284d7c78edb32dec2021b43d4dccbe101ce4/image-png/%7BAE9210C6-E45F-429B-B35E-4E9220B0C423%7D.png" />

I built the schematic for my NFC card in EasyEDA to harvest power from a phone tap and light up an LED. The design uses an NXP NT3H2111 chip for NFC communication and power harvesting, a PCB antenna to capture the phone's signal, a 220nF capacitor to smooth out the power, and an LED with a 47Ω resistor that turns on when power is detected. After verifying that the TSSOP-8 chip package uses standard pins without needing an exposed pad, the schematic is fully complete and ready for PCB layout.

**Total time spent: 0.5h**
