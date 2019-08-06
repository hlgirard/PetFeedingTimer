# PetFeedingTimer
Arduino-based project to put an end to your pet begging for food everytime someone comes into the kitchen


## Details

Do you live with roommates or a partner? Do you have a pet?
If so, this project is for you! No longer will your pet beg for every person who walks into the kitchen for food and get fed 3 times in the morning because you don't know if they got anything yet.

An arduino based device will tell you the last time your pet was fed on an LCD screen and LEDs will tell you at a glance whether you pet is lying to you !

## Repository strutcture

|__ CatFeedingTime_Nano contains the arduino code

|__ drawing contains Fritzing drawings of the circuit (breadboard and schematic)

## Device
![Picture of device](https://github.com/hlgirard/PetFeedingTimer/blob/master/drawing/picture.jpg)

## Usage

The device shows the time since last feeding on the LCD screen. Press the light button to turn the backlight of the LCD on.
The lit LED indicates ranges of time since the last feeding event:
- Green: less than 6 hours ago
- Orange: between 6 and 9 hours ago
- Red: more than 9 hours ago

When you feed your pet, press the fed button to reset the time. Pressing the fed button multiple times in a row sets the fed time back one hour for each press (for testing or after a loss of power).

### Materials

- Arduino board
- 3 LEDs (green, orange, and red) and corresponding resistors
- 2 buttons
- 16x2 char LCD

### Circuit Schematic

![Circuit Schematic](https://github.com/hlgirard/PetFeedingTimer/blob/master/drawing/CatFeedingInfo_Nano_schem.jpg)
