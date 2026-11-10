# NVNT's HammerCard Project

<img width="1896" height="576" alt="hammercard logo" src="https://github.com/user-attachments/assets/02d8835a-1b0d-445d-ae97-130e8977135b" />

HammerCard is a non-game cartridge for the Nintendo Switch 2 which exposes the pins of the cartridge slot for (hopeful) sniffing/interception. Drawing from the historical use and design of "middle-man" cartridges (think: GameShark for N64) which allowed for code interception and manipulation, the HammerCard project utilizes a Nintendo Switch 2 cartridge slot soldered onto the PCB with a pin-header in-between.

The goal of this project is providing hardware that may be usable for the community in their efforts.

---

## 📚 Table of Contents
- **Introduction**
  - [What Can I Do With This](#what-can-i-do-with-this)
  - [Goals](#goals)
  - [Status](#status)
  - [Warnings](#warnings)
- **Assets & Hardware Info**
    - [Nintendo Switch 2 Cartridge Slot Breakout Board](#nintendo-switch-2-cartridge-slot-breakout-board)
    - [HammerCard Proto](#hammercard-proto)
- [License](#license)

---

## What Can I Do With This?

Let's get the bad news out of the way. HammerCard, at least for now, isn't going to magically "unlock" things in your Nintendo Switch 2. However, the hope is that it can be used as a stepping stone or platform in furthering knowledge of the cartridge slot and game key encryptions in place.

---
## Goals

- ✅ Upload Version 0.1 "Switch 2 Cartridge Breakout Sniffer Mk2" - Without Nintendo Switch 2 Card Slot (DONE)
- ✅ Upload Version 0.2 "Switch 2 Hammer Card Mk1" Proto - With Nintendo Switch 2 Card Slot (DONE)
- 🔲 Fix Switch 2 Card/Cartridge Slot Pinout & Footprint
- 🔲 Make proper 3D enclosure, and re-work PCB to be smaller and better looking
- 🔲 TBD
---

## Status

Very early work in progress. In the file there is both the old version "Cartridge Breakout Sniffer Mk2" and the prototype of HammerCard.

---

## Warnings

- Use at your own risk. We are **not liable** for any damage to your drive, Switch 2, or other devices.
  
---

## Bill of Materials (BOM)

| Reference | Quantity | Description                             | Part Number        | Manufacturer   |
|-----------|----------|-----------------------------------------|--------------------|----------------|
|J3         | 1        | Nintendo Switch 2 Cartridge Slot        |*                   | On AliExpress  |
|J1         | 1        | 1x17 Pin Header                         | N/A                | *              |

---

### Nintendo Switch 2 Cartridge Slot Breakout Board

This is what started it all. A curiosity of sorts. A breakout cartridge for the Nintendo Switch 2 which breaks out the cartridge slot pins for probing.

<img width="2295" height="2605" alt="image" src="https://github.com/user-attachments/assets/a5a7e172-2c0a-463d-b6cb-a5b8bb63bdff" />

---

### HammerCard Proto

A very WIP, ugly, gumstick PCB prototype has been uploaded. The footprint/pinout of the Switch 2 game card slot isn't finalized and needs to be improved.

<img width="1023" height="862" alt="2050a543f42caad3d6315e8a7364d2c8" src="https://github.com/user-attachments/assets/86b3ebe7-ed99-4268-ab0c-7dde0641e35c" />

---
## License

<img width="210" height="112" alt="Open Source Licenses" src="https://github.com/user-attachments/assets/4e1478fe-8052-427a-bd83-dc1c1cdefa31" />

This hardware design is licensed under the **CERN Open Hardware License Version 2 – Strongly Reciprocal (CERN-OHL-S v2)**.

The software/firmware design is licensed under the **GNU General Public License v3.0 (GPLv3)**

The documentation and readme is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International (CC-BY-SA 4.0)**.

See [LICENSE](LICENSE.txt), [LICENSE-HARDWARE](LICENSE-HARDWARE.txt) and [LICENSE-DOCUMENTATION](LICENSE-DOCUMENTATION.txt) for more information.
