# Filafryer
A 3D printable filament dryer that can be configured and has optionally WiFi capability.

## Previous work
I started working on a filament dryer around a year ago, trying different heaters, different boxes, etc.
I got a version 1 working, but it was big, was heating unnecesary amount of air (too big volume of the box) and had mess of cables.
TODO: add pic of the first version

That's why I decided to make this Version 2, that is actually compact and more efficient, together with looking more cool.

I named it Filafryer because I got the idea from Air fryers used often as an alternative filament drying solution. Though in the end I created more of a mini oven.

## Features
- all the parts can be 3D printed on a 220mm³ build plate
- Partially printed box, uses 2020 extrusions for the main chamber.
- up to 70°C heating temp (proper insulation required) -- Will update this once I test it out.
- Uses a 250W (maybe two of them) **AC POWERED** PTC heater, for faster heating times.
- PTC controlled with SSR + combination of thermal fuse and a secondary relay for safety and reliability.
- Will be able to recirculate the air.
- Uses ESP32-S3 as the main board!

## Rough model of the idea I have

<img width="827" height="480" alt="image" src="https://github.com/user-attachments/assets/9d032621-1cf0-4322-8ceb-0f7cc858fdcd" />

As you can see, looks pretty much the same as a regular microwave, but works more like a toaster oven. The filament is going to be rotated around to be dryed evenly. In the back, there will be two valves that will allow intake and exhaust of the air.

There will be a small 12V power supply inside for the control board, all the electronics will be hidden in the compartment with the screen.

## WARNING
There can be work with AC power, do not recreate this project without having experience with working around HIGH VOLTAGES.
This can and will be a health risk if not done properly.
Also the SSR has chance of failing, this design should have all the counter measures to prevent thermal runaway.
But still KEEP AN EYE DURING USAGE.

## Parts list (BOM)
This is more a list to based it on, you can change up some components for now, until I come up with a PCB breakout
TODO
