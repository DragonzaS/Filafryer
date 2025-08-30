# Filafryer
A compact 3D printable filament drier that has can be configured and has optionally WiFi capability.

## Previous work
I started working on a filament dryer around a year ago, trying different heaters, different boxes, etc.
I got a version 1 working, but it was big, was heating unnecesary amount of air (too big volume of the box) and had mess of cables.
TODO: add pic of the first version

That's why I decided to make this Version 2, that is actually compact and more efficient, together with looking more cool.

I named it Filafryer because I got the idea from Air fryers used often as an alternative filament drying solution. Also was inspired by that for the design.

## Features
- all the parts can be 3D printed on a 220mm³ build plate
- Fully 3D printed box (ABS is needed)
- up to 70°C heating temp (proper insulation required) -- Will update this once I test it out.
- No need to do work with dangerous AC (if you can find a 12V 120W power supply, I didn't so I used a modular PSU, DON'T TRY THAT IT IS VERY DANGEROUS!)
- Uses ESP32-S3 as the main board!

## Rough model of the idea I have

<img width="1919" height="924" alt="image" src="https://github.com/user-attachments/assets/24da4233-c8e1-45b2-8f0a-9b61189024f5" />

There will be two compartments (top and bottom) with a fan + heater system, making the drying more even and also helps with circulating the air around the spool.

Power supply and maybe rest of the electronics will be in a separate box. I will try to design a PCB that will fit inside without it overheating (maybe on the top) so then only the PSU will have to be separated.

## WARNING
There can be work with AC power, do not recreate this project without having experience with this.
This can and will be a health risk if not done properly.
I HIGHLY recommend instead try to find a power supply with a wall plug and a barrel jack.
And NOT USE a modular PSU that has to be wired by someone.

## Roadmap
- Electronics of V1 ✔️
- New 3D printed box
- Software of V1 (running through ESPHome and Home assistant)
- New software
- New breakout board + V2 electronics (might be moved higher due to Grounded still running)
- Future plans not yet decided

## Parts list
This is more a list to based it on, you can change up some components for now, until I come up with a PCB breakout
TODO
