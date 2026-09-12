<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# [Runaway Aravind] 🎯


## Basic Details
### Team Name: [TEAM ALPHA]


### Team Members
- Team Lead: [G ARAIND] - [RIT]
- Member 2: [SIRIN J DEVASSIA] - [RIT]

### Project Description
[An ESP32-powered prank alarm robot designed to force chronic snoozers out of bed by actively running away. When a hand reaches out, ultrasonic sensors trigger the robot to reverse and dodge capture. Flipping the dummy "off" switch activates a trap routine that mocks the user and bolts backward at full speed.]

### The Problem (that doesn't exist)
[Traditional alarm clocks suffer from a fatal design flaw: they sit completely still and let you turn them off. Humanity's greatest morning crisis isn't lack of willpower, but the tragic, unaddressed injustice of alarm clocks not having high-torque wheels, evasive survival instincts, and a psychological trap designed to punish your lazy hands.]

### The Solution (that nobody asked for)
[An autonomous, sleep-depriving menace on wheels powered by an ESP32 microcontroller with an attitude problem.

Instead of politely chiming on a nightstand, this mechanical gremlin uses ultrasonic echolocation to actively dodge your groggy hands like a caffeinated roomba. To ensure maximum morning emotional damage, it features an enticingly large, clicky "OFF" switch. Flipping this switch doesn't silence the alarm—it registers as high treason. The robot unleashes an ear-piercing frequency, flashes mocking insults across its OLED screen, and fires both DC motors to maximum PWM reverse thrust, forcing you into an unprovoked cross-bedroom Olympic sprint before you've even opened both eyes.]

## Technical Details
### Technologies/Components Used
For Software:
- [C / C++ (Embedded)]
- [Arduino Core for ESP32]
- [Wire.h (I2C communication)

Adafruit_GFX.h (Core graphics display library)

Adafruit_SH110X.h (Hardware driver for 1.3" OLED displays)]
- [Arduino IDE (v2.x),Serial Monitor (115200 baud debugging)]

For Hardware:
- [ESP32 Dev Module (30-pin microcontroller board),L298N (or similar) Dual H-Bridge Motor Driver,2x BO DC Gear Motors with matching wheels
,HC-SR04 Ultrasonic Distance Sensor module,1.3-inch I2C Monochrome OLED Display (SH1106 controller),5V Active Buzzer,3-Position DPDT Rocker Switch (I - O - II dummy trap switch),External battery pack (e.g., 2x 18650 Li-ion batteries or 9V battery harness)]
- [Microcontroller Core: Dual-Core Tensilica Xtensa 32-bit LX6 running at up to 240 MHz,Motor PWM Frequency & Resolution: 5000 Hz at 8-bit resolution (values 0–255 via LEDC),Ultrasonic Operating Range: 2 cm to 400 cm with a 25 cm evasion threshold trigger,Display Resolution & Interface: 128x64 pixels over standard 400 kHz I2C (Address: 0x3C),Logic Voltage: 3.3V logic (ESP32) / 5V sensor & motor rail]
- [2WD robot chassis plate with caster wheelMale-to-Female, Female-to-Female, and Male-to-Male jumper wires,Micro-USB data cable (for code flashing and power debugging),Small precision screwdriver (for motor driver terminal blocks),Double-sided tape or hot glue gun (for mounting components)]

### Implementation
For Software:
# Installation
[commands]

# Run
[commands]

### Project Documentation
For Software:

# Screenshots (Add at least 3)
![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

# Diagrams
![Workflow](Add your workflow/architecture diagram here)
*Add caption explaining your workflow*

For Hardware:

# Schematic & Circuit
![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

# Build Photos
![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

### Project Demo
# Video
[Add your demo video link here]
*Explain what the video demonstrates*

# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- [Sirin J Devassia]: [Lead firmware developer; wrote and optimized the ESP32 embedded C++ code, implemented the ultrasonic evasion algorithms, and designed the SH1106 OLED display UI and animations.]
- [G ARAVIND]: [Hardware design & integration; assembled the 2WD robot chassis, wired the L298N motor driver and power distribution rails, and integrated the dummy rocker switch mechanism.]


---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



