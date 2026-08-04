---
title: A Teardown of the DTector Digivice (Revision 1)
author: hasan
date: 2026-08-04 19:30:00 -0400
categories: [Blogging, Tech]
tags: [writing, documentation, teardown, history]
img_path: /assets/d-tector_digivice/
render_with_liquid: false
---

# Background

I picked up an old broken D-tector Digivice. As a kid, I was always interested to see how they fit so much on such a small device.

I am relying on my love of retro history, archiving, and preservation to investigate this toy. Combining this with the things I want to learn, I figured this was a good project to start working on. My goal is to clean up the circuit, document it, and try to reverse engineer what I can.

For starters, I am not a Digimon expert. I simply had this toy as a kid and played it a lot. I did not watch the show much or play the card game, but I know I (might) have some old cards laying around which still have the "Digi-Digits" on them that you could enter into the digivice.

The DTector digivices were a set of toys that were released in 2002 which mimicked as a result of the popularity of the show Digimon. This toy from 2002 was a pedometer that would occasinoally require you to fight other digimon. The idea is that you would have an "encounter" while walking around 

I dont know much of the history of the other devices but I recall there were at least 2 versions. released in north america. More can be found here [https://wikimon.net/D-Tector_Toy](https://wikimon.net/D-Tector_Toy)

I know one version had "Speed Runner" (Version 1) and the other didn't (Version 2). I had both as a kid luckily. I do not know much outside of these two that were released elsewhere in the world.

This teardown is for Revision 1 (Tommy's device colour). All 5 characters had their own colour from what I remember.

For more history and information, please see the #Additional Sources section at the end of this page.

# Teardown

1. Exterior pictures
![Front](/front.jpg)
_Figure 1: Front face of the D-Tector_
![Back](/back.jpg)
_Figure 2: Back face of the D-Tector_
![Side](/side.jpg)
_Figure 3: Side_
![Top](/top.jpg)
_Figure 4: Top - This was used to connect to other D-Tectors to "battle"!_

2. Internals
![Full Teardown](/teardown_inside_all.jpg)
_Figure 5: Full Teardown_
![Circuit with CMOS](/full_circuit_with_CMOS.jpg)
_Figure 6: Circuit with a Corroded (?) CMOS_
![Other Components](/other_components_pedometer.jpg)
_Figure 7: The pedometer (circuit needs cleaning!!)_
![Removable Buttons](/removable_buttons.jpg)
_Figure 8: Removable buttons: Orange is the reset button, grey is the side button, the clear acrylic is in front of the scanner_
![Top of the Circuit](/top_circuit_scanner_red_black_wire_missing.jpg)
_Figure 9: Next to the scanner, there should be a red and black wire that are connected to the batter, but they fell off_

CPU seems to a be a .... 27AR_LM_393M cpu.
![CPU](/27AR_LM_393M_CPU.jpg)


This is a broken one. There seems to be some battery corrosion and wires that fell out . The red wire should go here, i have the black one too but it fell off and i have to re-solder it.

I could not access the front panel of the device as they are held by smaller screws. I broke one with just one turn of my screwdriver....  so I decided not to risk it :)

![middle_screws](/middle_screws.jpg)
_Figure 11: I broke one of these screws!_


# Next Steps
1. document the layout of the board
2. extract the firmware if possible 
3. Reverse engineer the layout and code

I don't know how to do this yet


# Additional Sources

[Wikimon article about the Toys](https://wikimon.net/D-Tector_Toy)  
[Fandom Article](https://digimon.fandom.com/wiki/Digivice#D-Tector)  
[Emulation project](https://k0as7.itch.io/) (no technical details)

I was unable to find any code related to extracted firmware or anything, but my knowledge on this subject is limited so perhaps I missed it.