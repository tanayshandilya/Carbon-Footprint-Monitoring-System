# Carbon-Footprint-Monitoring-System

**TABLE OF CONTENTS**

-   [INTRODUCTION](#introduction)
-   [MOTIVATION](#motivation)
-   [COMPONENTS DESCRIPTION](#components-description)
-   [PROPOSED MODEL](#proposed-model)
-   [DISCUSSIONS](#discussions)
-   [CONCLUSION](#conclusion)
-   [FUTURE SCOPE](#future-scope)
-   [REFRENCES](#references)

INTRODUCTION
------------
### **Carbon Footprint**

Climate Change (also known as Global Warming) is the name given to long term
changes to temperature on and around the Earth’s surface, which causes long term
shifts to weather patterns. Climate Change isn't limited to one region; it
impacts the whole of the Earth. It is causing polar ice sheets and glaciers to
melt; and sea levels to rise. Extreme weather events such as typhoons and
hurricanes are becoming more common in some regions of the world, while others
regions experience more punishing droughts and heat waves. Since 1958, CO2 has
been measured at the Mauna Loa Observatory in Hawaii. In 1958, the CO2
concentration in the atmosphere was measured at 316ppm, as of May 2016 it was
407ppm. Before the industrial revolution began (1880s), the CO2 concentration in
the atmosphere was measured at 280ppm and so in just 130 years, CO2
concentrations have increased by 45%.

### **IoT**

Internet of Things (IoT) is an ecosystem of connected physical objects that are
accessible through the internet. The ‘thing’ in IoT could be a person with a
heart monitor or an automobile with built-in-sensors, i.e. objects that have
been assigned an IP address and have the ability to collect and transfer data
over a network without manual assistance or intervention. The embedded
technology in the objects helps them to interact with internal states or the
external environment, which in turn affects the decisions taken.

The Internet of things is a great opportunity to effectively address the carbon
emissions from human activities. Through the communication of cars, appliances,
generators and phones, each machine will be able to receive feedbacks to know
efficient emission of toxic gases that constitute to carbon footprint generation
by an individual. Devices are connected to the web, and the data can be sent
using the protocol that communicates computers to the internet. The devices can
sense the environment and communicate with each other and may generally enable
automatic reply to challenging scheme without human interference. This paper
proposes use of loT for air pollution monitoring and identification of vehicles
causing pollution.

### **Environmental gas sensors** 

A broad definition of environmental monitoring would include all aspects of air
and water quality, soil contamination, electromagnetic radiation, noise, even
heat release and light source pollution. However, the major environmental gas
sensors are to monitor pollution in air, water, and soil. Environmental standard
concentration and threshold limit value for six important gases of air. Some
information about gas sensors on the base of most familiar metal oxides and
technological peculiarities of these sensors fabrication, which can be used for
such selection. Gas sensors for monitoring principal gases among air pollutants
are described in detail by using typical examples here.

### **Machine Learning**

A core objective of a learner is to generalize from its experience.
Generalization in this context is the ability of a learning machine to perform
accurately on new, unseen examples/tasks after having experienced a learning
data set. The training examples come from some generally unknown probability
distribution (considered representative of the space of occurrences) and the
learner has to build a general model about this space that enables it to produce
sufficiently accurate predictions in new cases.

The computational analysis of machine learning algorithms and their performance
is a branch of theoretical computer science known as computational learning
theory. Because training sets are finite and the future is uncertain, learning
theory usually does not yield guarantees of the performance of algorithms.
Instead, probabilistic bounds on the performance are quite common. The
bias–variance decomposition is one way to quantify generalization error.

For the best performance in the context of generalization, the complexity of the
hypothesis should match the complexity of the function underlying the data. If
the hypothesis is less complex than the function, then the model has under fit
the data. If the complexity of the model is increased in response, then the
training error decreases. But if the hypothesis is too complex, then the model
is subject to overfitting and generalization will be poorer.

In addition to performance bounds, computational learning theorists study the
time complexity and feasibility of learning. In computational learning theory, a
computation is considered feasible if it can be done in polynomial time. There
are two kinds of time complexity results. Positive results show that a certain
class of functions can be learned in polynomial time. Negative results show that
certain classes cannot be learned in polynomial time.

MOTIVATION
----------

Climate Change (also known as Global Warming) is the name given to long term
changes to temperature on and around the Earth’s surface, which causes long term
shifts to weather patterns. Climate Change isn't limited to one region; it
impacts the whole of the Earth. It is causing polar ice sheets and glaciers to
melt; and sea levels to rise.

With the use of M2M technology, the energy sector has the potential to save more
than 2 billion metric tons of carbon dioxide. It can do so by automating the
monitoring of machines, reducing the time spent accomplishing repetitive tasks
such as maintenance and reducing the costs of providing any service. IoT
machines can continually collect data on energy consumption and provide rigorous
analysis, making for efficiency and precision in operation.

Back in November, Sierra Wireless co-sponsored "In the Air," an Internet of
Things (IoT) design challenge organized by Element14. During the 4-month contest
period, 15 engineers accepted the challenge to use the provided IoT development
kit (which included the AirVantage IoT platform) to create solutions for a
cleaner, more breathable world. 

We were pleased and surprised by the impressive designs delivered by the contest
participants - picking one winner wasn’t an easy task. But among all the
creative and ambitious projects submitted, Christever del Rosario from New
Zealand was selected as the first prize winner for his "Carbon Footprint
Monitoring System."

This project got us inspired to create something similar which could be
implemented on a large scale, at a low cost thus we gathered the information
about the components that can reduce the cost of this project and to make the
system more efficient we also decided to utilize the effective suggestion
methods developed under the machine learning technology, which can make the
application of this device even more user friendly.

COMPONENTS DESCRIPTION
----------------------

### **ARDUINO**

![Image result for ARDUINO](https://i.imgur.com/OUmdwmB.png)

Arduino is an open-source platform used for building electronics projects.
Arduino consists of both a physical programmable circuit board (often referred
to as a microcontroller) and a piece of software, or IDE (Integrated Development
Environment) that runs on your computer, used to write and upload computer code
to the physical board.

The Arduino platform has become quite popular with people just starting out with
electronics, and for good reason. Unlike most previous programmable circuit
boards, the Arduino does not need a separate piece of hardware (called a
programmer) in order to load new code onto the board – you can simply use a USB
cable. Additionally, the Arduino IDE uses a simplified version of C++, making it
easier to learn to program. Finally, Arduino provides a standard form factor
that breaks out the functions of the micro-controller into a more accessible
package.

The Arduino hardware and software was designed for artists, designers,
hobbyists, hackers, newbies, and anyone interested in creating interactive
objects or environments. Arduino can interact with buttons, LEDs, motors,
speakers, GPS units, cameras, the internet, and even your smart-phone or your
TV! This flexibility combined with the fact that the Arduino software is free,
the hardware boards are pretty cheap, and both the software and hardware are
easy to learn has led to a large community of users who have contributed code
and released instructions for a huge variety of Arduino-based projects.

### **Gas Sensor MQ135**

![Related image](https://i.imgur.com/kH3y94O.jpg)

The MQ series of gas sensors utilizes a small heater inside with an electro
chemical sensor these sensors are sensitive to a range of gasses are used at
room temperature. MQ135 alcohol sensor is a Sno2 with a lower conductivity of
clean air. When the target explosive gas exists, then the sensor’s conductivity
increases more increasing more along with the gas concentration rising levels.
By using simple electronic circuits, it convert the charge of conductivity to
correspond output signal of gas concentration.

The MQ135 gas sensor has high sensitivity in ammonia, sulfide, benzene steam,
smoke and in other harm full gas. It is low cost and suitable for different
applications. Sensitive material of MQ135 gas sensor is SnO2, which with lower
conductivity in clean air. When the target combustible gas exist. The sensors
conductivity is more higher along with the gas concentration rising. Please use
simple electro circuit, Convert change of conductivity to correspond output
signal of gas concentration. MQ135 gas sensor has high sensitivity to Ammonia,
Sulfide and Benzene steam, also sensitive to smoke and other harmful gases. It
is with low cost and suitable for different application.

Used for family surrounding environment noxious gas detection device, apply to
ammonia, aromatics, sulfur, benzene vapor, and other harmful gases/smoke, gas
detection, tested concentration range: 10 to 1000ppm.

Characteristics

-   Good sensitivity to Harmful gases in wide range

-   High sensitivity to Ammonia, Sulfide and Benzene

-   Long life and low cost

-   Simple drive circuit

Application

-   Domestic air pollution detector

-   Industrial air pollution detector

-   Portable air pollution detector.

### **ESP8266 Serial Esp-01 WIFI Wireless**

![Related image](https://i.imgur.com/JX0khaW.jpg)

The ESP8266 Wi-Fi Module is a self-contained SOC with integrated TCP/IP protocol
stack that can give any microcontroller access to your WiFi network. The ESP8266
is capable of either hosting an application or offloading all Wi-Fi networking
functions from another application processor. Each ESP8266 module comes
pre-programmed with an AT command set firmware, meaning, you can simply hook
this up to your Arduino device and get about as much Wi-Fi-ability as a Wi-Fi
Shield offers (and that’s just out of the box)! The ESP8266 module is an
extremely cost effective board with a huge, and ever growing, community.

This module has a powerful enough on-board processing and storage capability
that allows it to be integrated with the sensors and other application specific
devices through its GPIOs with minimal development up-front and minimal loading
during runtime. Its high degree of on-chip integration allows for minimal
external circuitry, including the front-end module, is designed to occupy
minimal PCB area. The ESP8266 supports APSD for VoIP applications and Bluetooth
co-existence interfaces, it contains a self-calibrated RF allowing it to work
under all operating conditions, and requires no external RF parts.

#### **Ultra-low power technology** 

ESP8266 specifically for mobile devices, wearable electronics and networking
applications design and make the machine to achieve the lowest energy
consumption, together with several other patented technology. This
energy-efficient construction in three modes: active mode, sleep mode and deep
sleep mode type. When ESP8266 using high-end power management technology and
logic systems to reduce non-essential functions of the power conversion regulate
sleep patterns and work modes, in sleep mode, it consumes less than the current
12uA, is connected, it consumes less power to 1.0mW (DTIM = 3) or 0.5mW (DTIM =
10). Sleep mode, only calibrated real-time clock and watchdog in working
condition. Real-time clock can be programmed to wake ESP8266 within a specific
period of time. Through programming, ESP8266 will automatically wake up when
detected certain to happen. ESP8266 automatic wake-up in the shortest time, this
feature can be applied to the SOC for mobile devices, so before you turn Wi- Fi
SOC are in a low-power standby mode. To meet the power requirements of mobile
devices and wearable electronics products, ESP8266 at close range when the PA
output power can be reduced through software programming to reduce overall power
consumption in order to adapt to different applications.

PROPOSED MODEL
--------------

### **BLOCK DIAGRAM**

![Block Diagram](https://i.imgur.com/ENUiwtX.jpg)

### **WORK FLOW DIAGRAM**

![Flow Chart](https://i.imgur.com/41m27LF.jpg)

### **WORKING**

This project targets the use of gas sensors to monitor the carbon footprint
generated by cars and other heavy duty vehicles. First the gas sensor MQ-135
produces the data based on the gases contents in the environment (near the
vehicle). The MQ-135 produces an analog output; this analog output data is
forwarded to the Arduino controller. The controller is required to be programmed
to convert this analog data into a string, these data strings are then sent to
the server with the help of ESP 8266-01 Wi-Fi wireless module. The ESP 8266-01
is interfaced with the Arduino using the serial communication, this can be
achieved using the AT Command method or by using a programming language called
LUA Programming Language. In this case we use the AT Command method to interface
the Arduino with ESP 8266-01 to send the sensor data to the server. The server
used here is an Apache Server that supports different communication protocols
such as HTTP, TCP, etc. For this project we use the TCP Protocol. Data can be
sent or received from the server by different methods namely, GET, POST,
REQUEST. By using the GET method, the data is sent over the server. The server
end programming is done in such a way that is stores the received values into
the realtime database. The realtime database is used to update the value for
each user. This value from realtime database is used by the Machine Learning
algorithms that compares the latest updated value of the realtime database with
the previous records and standard limits. If all these values together are above
the limit of the standard carbon footprint limit, then an alert is generated by
the algorithm to the server which notifies the user about the exceeding limit of
Carbon Footprint so generated by the vehicle. If the algorithm finds that the
usage is within the limit of standard carbon footprint limit, it stores this
data into a readable no SQL database. This data is also used for a graphical
information display to the user mobile app or website.

#### **Gas Sensor**

Gas sensors are available in wide specifications depending on the sensitivity
levels, type of gas to be sensed, physical dimensions and numerous other
factors. This Insight covers a methane gas sensor that can sense gases such as
ammonia which might get produced from methane. When a gas interacts with this
sensor, it is first ionized into its constituents and is then adsorbed by the
sensing element. This adsorption creates a potential difference on the element
which is conveyed to the processor unit through output pins in form of current.
What is this sensing element? Is it kept in some chamber or is kept exposed? How
does it get current and how it is taken out? Let’s find out in this Insight!!!

The gas sensor module consists of a steel exoskeleton under which a sensing
element is housed. This sensing element is subjected to current through
connecting leads. This current is known as heating current through it, the gases
coming close to the sensing element get ionized and are absorbed by the sensing
element. This changes the resistance of the sensing element which alters the
value of the current going out of it.

The connecting leads of the sensor are thick so that sensor can be connected
firmly to the circuit and sufficient amount of heat gets conducted to the inside
part. They are casted from copper and have tin plating over them. Four of the
six leads (A, B, C, D) are for signal fetching while two (1,2) are used to
provide sufficient heat to the sensing element.

The pins are placed on a Bakelite base which is a good insulator and provides
firm gripping to the connecting leads of the sensor.

#### **Arduino Board**

The Arduino hardware and software was designed for artists, designers,
hobbyists, hackers, newbies, and anyone interested in creating interactive
objects or environments. Arduino can interact with buttons, LEDs, motors,
speakers, GPS units, cameras, the internet, and even your smart-phone or your
TV! This flexibility combined with the fact that the Arduino software is free,
the hardware boards are pretty cheap, and both the software and hardware are
easy to learn has led to a large community of users who have contributed code
and released instructions for a huge variety of Arduino-based projects.

For everything from robots and a heating pad hand warming blanket to honest
fortune-telling machines, and even a Dungeons and Dragons dice-throwing
gauntlet, the Arduino can be used as the brains behind almost any electronics
project.

What's on the board?

There are many varieties of Arduino boards (explained on the next page) that can
be used for different purposes. Some boards look a bit different from the one
below, but most Arduinos have the majority of these components in common:

Power (USB / Barrel Jack)

Every Arduino board needs a way to be connected to a power source. The Arduino
UNO can be powered from a USB cable coming from your computer or a wall power
supply (like this) that is terminated in a barrel jack. In the picture above the
USB connection is labeled (1) and the barrel jack is labeled (2).

The USB connection is also how you will load code onto your Arduino board. More
on how to program with Arduino can be found in our Installing and Programming
Arduino tutorial.

NOTE: Do NOT use a power supply greater than 20 Volts as you will overpower (and
thereby destroy) your Arduino. The recommended voltage for most Arduino models
is between 6 and 12 Volts.

Pins (5V, 3.3V, GND, Analog, Digital, PWM, AREF)

The pins on your Arduino are the places where you connect wires to construct a
circuit (probably in conjuction with a breadboard and some wire. They usually
have black plastic ‘headers’ that allow you to just plug a wire right into the
board. The Arduino has several different kinds of pins, each of which is labeled
on the board and used for different functions.

GND (3): Short for ‘Ground’. There are several GND pins on the Arduino, any of
which can be used to ground your circuit.5V (4) & 3.3V (5): As you might guess,
the 5V pin supplies 5 volts of power, and the 3.3V pin supplies 3.3 volts of
power. Most of the simple components used with the Arduino run happily off of 5
or 3.3 volts. Analog (6): The area of pins under the ‘Analog In’ label (A0
through A5 on the UNO) are Analog In pins. These pins can read the signal from
an analog sensor (like a temperature sensor) and convert it into a digital value
that we can read. Digital (7): Across from the analog pins are the digital pins
(0 through 13 on the UNO). These pins can be used for both digital input (like
telling if a button is pushed) and digital output (like powering an LED). PWM
(8): You may have noticed the tilde (\~) next to some of the digital pins (3, 5,
6, 9, 10, and 11 on the UNO). These pins act as normal digital pins, but can
also be used for something called Pulse-Width Modulation (PWM). We have a
tutorial on PWM, but for now, think of these pins as being able to simulate
analog output (like fading an LED in and out). AREF (9): Stands for Analog
Reference. Most of the time you can leave this pin alone. It is sometimes used
to set an external reference voltage (between 0 and 5 Volts) as the upper limit
for the analog input pins.

Reset Button

Just like the original Nintendo, the Arduino has a reset button (10). Pushing it
will temporarily connect the reset pin to ground and restart any code that is
loaded on the Arduino. This can be very useful if your code doesn’t repeat, but
you want to test it multiple times. Unlike the original Nintendo however,
blowing on the Arduino doesn’t usually fix any problems.

Power LED Indicator

Just beneath and to the right of the word “UNO” on your circuit board, there’s a
tiny LED next to the word ‘ON’ (11). This LED should light up whenever you plug
your Arduino into a power source. If this light doesn’t turn on, there’s a good
chance something is wrong. Time to re-check your circuit!

TX RX LEDs

TX is short for transmit, RX is short for receive. These markings appear quite a
bit in electronics to indicate the pins responsible for serial communication. In
our case, there are two places on the Arduino UNO where TX and RX appear – once
by digital pins 0 and 1, and a second time next to the TX and RX indicator LEDs
(12). These LEDs will give us some nice visual indications whenever our Arduino
is receiving or transmitting data (like when we’re loading a new program onto
the board).

Main IC

The black thing with all the metal legs is an IC, or Integrated Circuit (13).
Think of it as the brains of our Arduino. The main IC on the Arduino is slightly
different from board type to board type, but is usually from the ATmega line of
IC’s from the ATMEL company. This can be important, as you may need to know the
IC type (along with your board type) before loading up a new program from the
Arduino software. This information can usually be found in writing on the top
side of the IC. If you want to know more about the difference between various
IC’s, reading the datasheets is often a good idea.

Voltage Regulator

The voltage regulator (14) is not actually something you can (or should)
interact with on the Arduino. But it is potentially useful to know that it is
there and what it’s for. The voltage regulator does exactly what it says – it
controls the amount of voltage that is let into the Arduino board. Think of it
as a kind of gatekeeper; it will turn away an extra voltage that might harm the
circuit. Of course, it has its limits, so don’t hook up your Arduino to anything
greater than 20 volts.

#### **ESP8266-01**

The ESP8266 can be controlled from your local Wi-Fi network or from the internet
(after port forwarding). The ESP-01 module has GPIO pins that can be programmed
to turn an LED or a relay ON/OFF through the internet. The module can be
programmed using an Arduino/USB to TTL converter through the serial pins (RX,
TX).

Connecting the Hardware to Your ESP8266

We can either use a USB to TTL converter or use an Arduino to program the
Esp8266. Here there are three methods you can follow to upload the code to
ESP8266, select the one which suits you best. Refer the following diagrams for
each and set up the hardware accordingly.

1. USB to TTL Converter Using DTR Pin

If you’re using a USB to TTL converter which has a DTR pin, then uploading will
go smoothly. Please be informed that Serial monitor will not work anymore while
doing this.

Using Arduino Uno to Flash the Code to the ESP8266

You can use the Arduino UNO to flash the code to ESP8266 ESP-01. While uploading
the code, follow the same procedure to keep the flash button pressed while you
once click on reset and release the flash button.

ARDUINO —————\> ESP8266 ESP-01

GND———————-\>GND

TX————————\>TX

RX————————\>RX

Reset Button————\>RST

Flash Button————\>GPIO0

DISCUSSIONS
-----------

### **The Earth has been getting warmer**

2016 was the hottest year on record, according to separate analyses by
scientists at NASA’s Goddard Institute for Space Studies (GISS) and the National
Oceanic and Atmospheric Administration (NOAA). It was also the third year in a
row to set a new record for global average surface temperatures. This
record-breaking heat is part of a long-term warming trend. The Earth’s average
surface temperature has risen about 1.1 degrees Celsius since the late 19th
century, when modern record-keeping began, and is projected to rise further over
the next hundred years or so.

The warming, most of which has happened in the past 35 years, is being driven
largely by increased carbon dioxide and other man-made emissions into the
atmosphere. We’ve now had 627 months warmer than normal, when compared with an
1881-1910 baseline. If you were born later than December 1964, you’ve never
known a month cooler than average, according to Climate Central.

Global warming is caused by the emission of greenhouse gases. 72% of the totally
emitted greenhouse gases is carbon dioxide (CO2), 18% Methane and 9% Nitrous
oxide (NOx). Carbon dioxide emissions therefore are the most important cause of
global warming. CO2 is inevitably created by burning fuels like e.g. oil,
natural gas, diesel, organic-diesel, petrol, organic-petrol, ethanol. The
emissions of CO2 have been dramatically increased within the last 50 years and
are still increasing by almost 3% each year.

Since the major cause of the global warming, and the major source of CO2
emission is from cars it got us thinking how we could reduce it using some
electronics. Currently, there are already a number of initiatives and
regulations promoting the reduction of carbon footprint that mostly adopted by
commercial/industrial companies around the globe. However, it should not stop
there.

With all the advancement in technology, it is now more economical to build
devices that can be installed for residential applications, such as the one
being proposed here: a real-time carbon footprint monitoring system, to provide
awareness about the household’s carbon footprint and is the first step towards
the reduction of CO2 emissions. Then we can all contribute to this goal of
transforming our world into a healthier place to live in.

Thus with some further research we came across a project that provided a
solution using Internet of Things technology to sense the environment we live in
and how IoT can help us build a cleaner and less polluted world.

This project got us inspired to create something similar which could be
implemented on a large scale, at a low cost thus we gathered the information
about the components that can reduce the cost of this project and to make the
system more efficient we also decided to utilize the effective suggestion
methods developed under the machine learning technology, which can make the
application of this device even more user friendly.

CONCLUSION
----------

The statistical data from the global climate analysis shows that gases from the
combustion of the fossil fuel plays the major role in carbon footprint
increment. Thus to control the amount of carbon footprint generated by an
individual this project can help spread awareness about individual response to
global warming. And since the internet penetration is more than ever today it is
much easier and convenient to collect the data produced by the air quality
sensor.

For every vehicle equipped with this module the usage and secretion of toxic
gases like CO2, Smoke, NOx, etc. can be measured and stored for analysis of the
carbon footprint so generated by the vehicle. The machine learning algorithms
can also suggest methods to limit the usage the vehicle in order to improve the
health of environment and the individuals as well. The health of the engine that
drives the vehicle also plays an important role in this, so this system can also
monitor the health of the vehicle. Not only this system applicable for an
individual, but it can also be used to collect the data over many users in a
large geographical area to measure the carbon footprint over large areas.

FUTURE SCOPE
------------

Further research is needed to accurately relate the ppm value of the sensor to
CO2 emission. Installing a digital fuel meter or connect through the CAN bus to
accurately measure fuel consumption. As an additional feature, using the
recorded distance traveled and CO2 emission level (via sensor), the system can
send notifications to the user that the vehicle must be serviced.

The power monitoring feature (via ACS712) needs to be implemented. Implement
ambient light sensing for the smart switch implementation. Report humidity and
temperature sensing to AirVantage. Re-spin a smaller hardware that will fit
inside standard wall socket flush box. Re-spin hardware to support additional CT
sensor (i.e. for monitoring hot water power usage). Report rechargeable battery
state/condition. Report BQ25504 charging status.

To be fully implemented. Add microphone and implement some sort of voice
detection to identify presence. Create additional capes for the Beagle Bone
Black to support additional communication mediums, i.e. ZigBee or RF, to support
additional off-the-shelf sensors. This improvement is more for Sierra Wireless,
some of them might be implemented but I haven't had the time to dig deeper,
regardless these are nice to haves.

It would be nice to support more data series on monitoring charts, atm, it can
only do 3 series max. It would be nice to support other charts aside from the
line chart, i.e support for bar graph and pie charts. It would be nice for
charts to support presentation of DateTime or Timespan in charts. Possibly the
most important one, it would be ideal if there are downloadable libraries that
can be used for ease of interfacing with AirVantage.

REFERENCES
----------

### **Project Inspiration –** 

Element14 Design Challenge winner “In The Air Project” created by **Inderpreet
Singh.**

Link to project:

*https://www.element14.com/community/community/design-challenges/in-the-air-design-challenge/*
*https://www.researchgate.net/publication/275824203_ARIIMA*
*https://www.arduino.cc/en/Guide/Introduction*
*https://www.udemy.com/machinelearning*
