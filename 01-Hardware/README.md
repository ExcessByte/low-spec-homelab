# The Hardware

This hardware is ancient. It is a **Wipro LittleGenius (WLG7B1623V)** laptop from the late 2000s. The original plastic body was ... good actually. Nice keyboard too. Just my opinion, and I have not used a laptop for more than 1 day. The CPU cooler fan was completely dead, and laptop replacement fans cost way too much money for a project like this. 

Because of the dead fan, The CPU keeps overheating just after 4-5mins of simple usage. So I decided to completely strip it down and build a custom "case" for it. 

---

## The DIY Wooden "Case"

I quickly realized I don't have the woodworking skills to build something sleek and beautiful.

### 1. The Base
I took a piece of soft wood and cut it down to fit the motherboard and the length of the hard disk. I wanted to make it compact, but because the hard drive sticks out, the final footprint ended up being back to original laptop dimensions anyway. I couldn't just leave the drive hanging!

### 2. Custom Wood Standoffs
I didn't want the motherboard resting directly on its own underside components (which would put uneven stress on the PCB). 
* I cut tiny rectangles of wood.
* I glued them down as DIY standoffs matching the original laptop screw hole locations.

### 3. Securing it with... Push Pins 📌
Instead of proper mounting screws, the motherboard is held onto the wooden standoffs using basic **push pins**. Why?
1. I didn't have the original screws.
2. The proprietary display cable connector is on the *underside* of the motherboard. I have to constantly flip the board over to debug things, and pulling out push pins is way faster than unscrewing a board every time!

---

## Power Optimization

To make this the ultimate low-power homelab, I stripped away absolutely everything that wasn't strictly necessary to boot the system:

* **Removed:** Built-in display panel, trackpad, keyboard, Optical Disc Drive and also the wifi-card (it was either dead or wasn't being detected by any Linux distros).

This minimizes power consumption and keeps the system incredibly lightweight. I cannot accuratly give the usage metrics because I don't have the tools but since the adapter is 65W (20V and 3.25A), It probably draws less than that... 😉
