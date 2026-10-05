---
weight: 11
title: "Step-by-step Minisumo"
description: ""
icon: "article"
date: "2026-10-05T14:13:58+02:00"
lastmod: "2026-10-05T14:13:58+02:00"
draft: false
toc: true
------

- Obtain Components and Chassis (See [Bill of Materials below](#bill-of-materials)) or via a kit @ CRF while supplies last!
- Download the `minisumo.ino` file from [releases on the right side](https://github.com/ChalmersRobotics/minisumoplusplus2027/releases)
- Build the robot according to the [instructions below](#soldering-the-pcb)
- Upload the code to the robot as in the [instructions](programming) or as documented below.


## Instructions for pcb assembly / soldering incl tips and tricks
- [ ] tbd details expected to be filled in after prototypes received and lessons learned rolled in.

## Soldering 
The kit requires soldering, if you are not experienced soldering then **PRACTICE BEFORE SOLDERING COMPONENTS TO THE MINISUMO++2027 PCB - BOTH SOLDERING AND DESOLDERING (in case mistakes happen..)!!** 

Before soldering, ask a knowledgeable friend or please check online tutorials eg [pinheaders youtube short](https://www.youtube.com/shorts/PbAXsy-kIVU), or [wires to pcb with autofeed](https://www.youtube.com/watch?v=vhzhHQ49hIc), or [desoldering a pin header](https://www.youtube.com/watch?v=PI3e4P3qVKE), or [soldering castellated pcb smd](https://www.youtube.com/watch?v=rGvvwXrv310), or [general desoldering](https://www.youtube.com/watch?v=bG7yW9FigJA), or [desoldering by adding material](https://www.youtube.com/shorts/H6U1gfKOPl8), etc..

Materials needed (minimum)

- Understanding of soldering, patience and focus - soldering is not completely safe can cause health issues and is hot which can burn skin and ignite fires if care is not taken for yourself, those around you and the environment where you solder
- Well ventilated area or a good fan to evacuate fumes as the smoke is not healthy to breath in regularly in quantity - eg [hazards and health efects of solder fumes](https://www.weldminds.com/hazards-and-health-effects-of-solder-fumes/) ) and wash hands after handling solder.
- Soldering iron and something to hold it when you are not holding it (it's hot so be careful!)
- Solder (different types require different temperatures) 
- Pliers that can cut and hold (to hold hot things).
- Surface to solder on that is not going to get destroyed or burnt from the heat/solder - a block of wood can do.

Also recommended if possible:

- Flux (to aid solder wicking)
- "Helping hands" for holding components, wires in needed positions
- Wire strippers
- Wire cutters
- Desoldering equipment - braiding (solder wick), sucker, thick copper wire
- Magnifier 
- Good light

### Headers
The kit requires using male and female headers that will be [soldered](#Soldering) AND they need to be adjusted to the correct sizes that are required. if you are not experienced with this ask a knowledgeable friend and watch some videos eg [pin headers - sodlering,cutting, male, female, etc](https://www.youtube.com/watch?v=qz9Ryos1_GY)

Materials needed (minimum)
- Pliers that can cut and hold

## Bill of Materials
The materials needed for the project is:
- PCB
- 3D printed chassis
- ESP32 C6 Supermini
- Motor driver: L298N
- Ultrasonic sensor: HC-SR04
- IR sensor: v183
- Cables

![test image](/images/parts.webp)

# Soldering the PCB
The order which we recommend is

1. Pins on Buck-boost converter and corresponding headers on the PCB. (4 single pins)
2. Pins on ESP and headers on PCB (2 x 10 pins)
3. Switch directly through PCB (hard to reach!) and or on wires
4. Pins and headers for motor driver (4 pins + 2 pins)
5. Header for the sensors (10 pins)
6. Battery-holder (2 plates) 
