# Bounty-projects

## Table of Listed Projects

- Three Stars
  - Smart mug matt
  - Arduino based microservo robotic arm
- Two Stars
  - Configurable Mechanical Keyboard
  - Bicycle alarm system

- One Star
  - 7-segment Display PCB

## Project description and specification

### Arduino based robotic arm

**Difficulty: 3 stars**

What's cooler than building a robotic arm from scratch! The bounty will be assessed based on its functionality, efficiency and appearance.

#### Specification:

- The robotic arm should pick up these five objects: Marble, cloth, water, 3d printed Pikachu and pencil.
- You may use stepper motors, microservos or regular motors.
- For the 3D printing, Autodesk Fusion 360 or SolidWorks are recommended.
- Please read the 'Arduino based microservo arm' documentation in the projects page for reference. Please try not to copy any pre-existing designs.

### Smart mug matt

**Difficulty: 3 stars**

Drinking water is important to our health. According to [NHS](https://www.nhs.uk/live-well/eat-well/food-guidelines-and-food-labels/water-drinks-nutrition/), people should drink 6 to 8 cups of water every day. However, sometimes we often forget to drink water especially during the busy period, so we want to make a mug matt (or an attachment at the bottom of the mug) which can detect how much water you drink everytime you put the mug onto the matt, and to record the data to keep track whether you drink enough water or not.

#### Specification:

- The whole project should be on a PCB in a small form factor, preferably waterproof
- It should have the accuracy to ~10mL
- It should be able to upload data to a APP or a website, we suggest you to use Blink to connect between ESP32 MCU to phone, you can use other implementation as well
- It should be able to generate a weekly report based on the water intake
- It should remind the user to drink water if it detects the user haven't drink any water for 3 hours. The reminder can be a short vibration or a push notification on the app

### Bicycle alarm system

**Difficulty: 2 stars**

- The whole system should be enclosed in a small 3D printed shell that is easy to attach to the bike frame.
- It is based on a microcontroller that has bluetooth function
- It should have battery life longer that 1 week
- (Optional) It should come with the mobile app (for example, Blynk) that can keep the bike status up to date and push notification when the suspicious activity is detected.
- It should shock the person who it attempting to steal the bike with **EXTRA BEEFED UP 32V INPUT BUZZER**



### Configurable Mechanical Keyboard

**Difficulty: 2 stars**

This project is all about matrix keyboard, which can be a quite interesting and adventurous topic to explore. There is a big community about mechanical keyboard, all the way from the custom firmware to the difference between different springs inside the keyboard switch. It will be a great fun to play around!

As Electrical Engineers, this project mainly focuses on the working mechanism of a keyboard. A keyboard usually has many keys, but our microcontroller has limited pin count. To register many key inputs by using limited IO on a microcontroller could be a challenge, which will be the part that we will focus on.

#### Specification:

- The keyboard should have more than 16 keys (it should have the same amount or more keys than a regular numpad)
- It should have a polling rate equal to or more than 250Hz
- It should resolve the input conflict while multiple keys are pressed at the same time
- It should have a indicator and a layer switch function. Using numpad as an example, it should have one `num lock` key and performs different function when the `num lock` status is on or off
- Bonus: Adding a OLED display or a Rotary Encoder will be a **PLUS**, which will make this project from 2 stars to 3 stars with better reward. And over all, *it will be a lot of fun!*

### 7-segment Display, Extension

**Difficulty: 1 star**

Make extention of our old [7-segment Display](https://github.com/Fleming-Society/7-Segment-Display-Project) project, here are the specifications:

- Make a library for controlling the display, it should be a `.h` header file that people can include in their Arduino code
- It should be a small form factor PCB with programmable USB-C port
- It should have slots to attach different sensors, both analog and I2C
- It should be able to attach a swappable battery

Here are some suggested extension projects you can make:

- Thermometer to control the frying oil temperature
- CO2 meter
- Make a library for rolling numbers, so that it can display longer text like telephone number

# Prizes for the Bounty

**£100 Gift Card / Voucher of your choice for 3 Stars**

**£50 Gift Card / Voucher of your choice for 2 Stars**

**£10 Gift Card / Voucher of your choice for 1 Stars**

**You will be presented in the "Hall of Fame" on our Fleming Society website alongside with your project!**

# Contact

Need any components for the project? Ask any of our Fleming Society members or email us at flemingsociety@ee.ucl.ac.uk. It is best to provide Farnell and RS link for your components

Finished your project? Ready for your prize and find a place in Fleming Society website? Send us a mail at flemingsociety@ee.ucl.ac.uk and we will get it sorted. 

