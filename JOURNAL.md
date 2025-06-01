---
title: "K2-Mini Macropad"
author: "Akshat K"
description: "A 4x4 macropad inspired by the Keychron K2."
created_at: "2025-06-01"
---

## 1st of June: Hardware!
I followed the tutorial on the official Hackpad website and also understood the matrix wiring concept (which I found pretty cool) in order to draw-up the schematic. Thankfully, both my 4x4 matrix and the EC11 rotary encoder with the momentary push button *just* fit on all of the XIAO RP2040's pins.

![](images/schematic.png)

The tutorial was quite helpful and apart from getting used to some of KiCad's shortcuts and functions and finding symbols, the schematic didn't take too long.

**Total time spent:** 2.5h

Following the tutorial, I lined up all my switches in the PCB editor, and placed the XIAO RP2040 and EC11 on near the top. I really squeezed everything in, making sure the layout was as compact as possible without much unused space on the outside of the PCB. I also now understood the concept of routing and what it means physically on a PCB - I'll route everything next.

![](images/pcb_unrouted.png)

**Total time spent:** 0.5h