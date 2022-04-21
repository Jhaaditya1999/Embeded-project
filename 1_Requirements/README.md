# Introduction
The Heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the activities of the control system are done on a microcontroller called Atmega328.
## Research
Seat warmers were first introduced by Cadillac in 1966 to help with backaches. Some vehicles come with car seat warmers, which heat up the seat with the push of a button. Normally the buttons are located on the side of the driver and passenger door. In some vehicles, just the bottom of the seat warms up, where in others both the bottom and back warm up.
## Benefits
Heated seats can make cars much more comfortable in the winter, or for those who often get cold even in the summer. The heater in most vehicles work well, but the car’s seat warmer is close to your body allowing you to warm up faster. In some cases, the seat warms up before the rest of the vehicle does.

## Features
A new feature is seats that use a single component to heat and cool the seat. Due to the complexity of the system, all of the functions are computer controlled. This means that diagnostics and repairs are more in depth. However, this also means that DTCs may be set if there are any malfunctions. A scan tool will be required to pull these trouble codes and diagnose any issues.
## Functionality
- When the two switches are closed, the first LED glows indicating the actuation of the system and the heater
- Next the analog input from the temperature sensor is received and digitized
- The digitized temperature input is visualized using Pulse Width Modulation
- The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor
## 4 W's and 1 H
### Who
Every person who wants high temperature and in low temperature region people can be benified.

### What
A Hotseat is a application where one can adjust their requied temperature to the seat to get comfort from the environment temperatures.

### When
Mostly in winter seasons and almost in every regions it can start now

### Where
It can be implemented in low temperature regions

### How
This application was developed in SimulIDE using CodeBlocks
## SWOT Analysis
**Strength** The advantage of such devices is that you can not wait until the entire salon warms up, and immediately go on business. After all, heating has a local effect, so they do their job in 2-5 minutes.
**Weakness

- If you do not follow the recommendations and go too far with the temperature, this can lead to a decrease in the driver’s attentiveness, cause fatigue and headaches, and also increase the risk of catching a cold due to a violation of the body’s temperature regime
- The power cord is plugged in only after you fix the cape
- If you spill any liquid on the heater cover, immediately turn off the device
- If you leave the car, do not leave the device turned on
- You can not wash the capes, iron, maximum-shake
- Use dry bags to store the heater

**Opportunities** The advanced technologies in automotive seat heaters are predicted to increase the growth of the market in the review period. The latest features like modern seat heaters like consistent and controlled warmth, heating level adjustment are attracting the consumers and are expected to propel the market growth. Growing demand for comfort and energy capabilities in vehicles is accelerating market growth.

**Threats**

- A lack of regulation for these seats has left consumers more open to injuries
- Within 10 minutes at 120 degrees an individual can experience third-degree burns. For those with the inability to feel the temperature at the time, this can prove even more dangerous. Those who have been diagnosed with conditions such as paralysis, diabetes, and neuropathy are less like to feel the heat in their lower extremities
- High electrical resistance could cause the heater pad in the seat to overheat
## High Level Requirements

|ID|Description|Status|
|--|-----------|------|
|HLR1|	When the two switches are closed, the first LED glows indicating the actuation of the system and the heater|	Implemented|
|HLR2|	Next the analog input from the temperature sensor is received and digitized|	Implemented|
|HLR3	|The hard disk must be 4 GB	|Implemented|
|HLR4	|The web browser must be Microsoft Internet Explorer with a resolution of at least 800 * 600|	Implemented|
## Low Level Requirements
|ID|	Description	|Status|
|--|--------------|------|
|LLR1	|The digitized temperature input is visualized using Pulse Width Modulation	|Implemented|
|LLR2|	The system runs effectively on Windows 2000 server but it will also run equally well on compatible operating systems	|Implemented|
|LLR3|	The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol and here the data is displayed on the serial monitor	|Implemented|
