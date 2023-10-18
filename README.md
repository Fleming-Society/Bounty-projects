# Bounty-projects

## Table of Listed Projects

- Three Stars
  - Smart mug matt
- Two Stars
  - Configurable Mechanical Keyboard

- One Star
  - 7-segment Display PCB

## Project description and specification

### Configurable Mechanical Keyboard

**Difficulty: 2 stars**

This project is all about matrix keyboard, which can be a quite interesting and advanturous topic to explore. There is a big community about mechanical keyboard, all the way from the custom firmware to the difference between different springs inside the keyboard switch. It will be a great fun to play around!

As Electrical Engineers, this project mainly focuses on the working mechanism of a keyboard. A keyboard usually has many keys, but our microcontroller has limited pin count. To register many key inputs by using limited IO on a microcontroller could be a challenge, which will be the part that we will focus on.

#### Specification:

- The keyboard should have more than 16 keys (it should have the same amount or more keys than a regular numpad)
- It should have a polling rate equal to or more than 250Hz
- It should resolve the input conflict while multiple keys are pressed at the same time
- It should have a indicator and a layer switch function. Using numpad as an example, it should have one `num lock` key and performs different function when the `num lock` status is on or off
- Bonus: Adding a OLED display or a Rotary Encoder will be a **PLUS**, which will make this project from 2 stars to 3 stars with better reward. And over all, *it will be a lot of fun!*

### Smart mug matt

**Difficulty: 3 stars**

Drinking water is important to our health. According to [NHS](https://www.nhs.uk/live-well/eat-well/food-guidelines-and-food-labels/water-drinks-nutrition/), people should drink 6 to 8 cups of water every day. However, sometimes we often forget to drink water especially during the busy period, so we want to make a mug matt (or an attachment at the bottom of the mug) which can detect how much water you drink everytime you put the mug onto the matt, and to record the data to keep track whether you drink enough water or not.

#### Specification:

- The whole project should be on a PCB in a small form factor, preferably waterproof
- It should have the accuracy to $\plusmn 10mL$
- It should be able to upload data to a APP or a website, we suggest you to use Blink to connect between ESP32 MCU to phone, you can use other implementation as well
- It should be able to generate a weekly report based on the water intake
- It should remind the user to drink water if it detects the user haven't drink any water for 3 hours. The reminder can be a short vibration or a push notification on the app

### 7-segment Display, Extension

**Difficulty: 1 star**

Make extention of our old 7-segment Display project, here are the specifications:

- Make a library for controlling the display, it should be a `.h` header file that people can include in their Arduino code
- It should be a small form factor PCB with programmable USB-C port
- It should have slots to attach different sensors, both analog and I2C
- It should be able to attach a swappable battery

Here are some suggested extension projects you can make:

- Thermometer to control the frying oil temperature
- CO2 meter
- Make a library for rolling numbers, so that it can display longer text like telephone number
