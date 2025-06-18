# arduino
 An electronic component.
***

•Arduino is an open-source platform used for building electronics projects.

• It is a developement board developed by Arduino.cc and is based on Atmega328 Microcontroller.

•The software used for writing, compiling & uploading code to Arduino boards is called Arduino IDE (Integrated Development Environment), which is free to download from Arduino Official Site.

•It has an operating voltage of 5V while the input voltage may vary from 6V to 12V.
 
## arduino structure 
![ard](https://cdn.sparkfun.com/assets/b/f/e/9/c/513824face395f6d3d000000.png)

### 1) Power source
 The Arduino UNO can be powered from a USB cable coming from your computer (1) or a wall power supply that is terminated in a barrel jack (2).   
The USB cable also helps to upload code into the board.

### 2)Pins 
-This includes 5V, 3.3V, GND, Analog, Digital, PWM, AREF,Vin pins.
-The pins on Arduino are the places where you connect wires to construct a circuit ( which is generally through breadboard).The Arduino has several different kinds of pins, each of which is labeled on the board and used for different functions.

i) __GND (3)__: Short for ‘Ground’. There are several GND pins on the Arduino, any of which can be used to ground your circuit.  

ii) __5V (4) & 3.3V (5)__: The 5V pin supplies 5 volts of power, and the 3.3V pin supplies 3.3 volts of power.

iii) __Analog (6)__: The pins under the ‘Analog In’ label (A0-A5 on the UNO) are Analog In pins. These pins can read the signal from an analog sensor (like a temperature sensor) and convert it into a digital value which can be read.

iv) __Digital (7)__: The digital pins (0-13 on the UNO). These pins can be used for both digital input  and digital output.

v) __PWM (8)__: The tilde (~) next to the digital pins (3, 5, 6, 9, 10, and 11 on the UNO) represents PWM. These pins act as normal digital pins, but can also be used Pulse-Width Modulation (PWM). These are used for converting digital signals to analog signals for results.

vi) __AREF (9)__: Stands for Analog Reference. It is used to set an external reference voltage (between 0 and 5 Volts).
### 3) Reset Button
Arduino has a reset button (10). Pushing it will temporarily connect the reset pin to ground and restart any code that is loaded on the Arduino. 

### 4) Power LED Indicator
There’s a tiny LED next to the word ‘ON’ (11). This LED should light up whenever you plug your Arduino into a power source. This tells us if the working condition of the circuit board is perfect or not.

### 5) TX RX LEDs
TX is short for transmit, RX is short for receive.These LEDs will give us visual indications whenever our Arduino is receiving or transmitting data during uploading code onto the board.

### 6)Voltage Regulator
The voltage regulator  controls the amount of voltage that is let into the Arduino board which is upto 20V.
***

## Features
1) ATmega328P microcontroller ( 16Mhz).  

2)Digital I/O pins that can also serve as Pulse Width Modulation (PWM) outputs

3)Analog-to-Digital Converter (ADC), supports 10-bit resolution

4)Power the boards via USB, an external power supply, or a voltage regulator

5)Serial (UART), I2C, and SPI communication interfaces.

6)USB Interface
-Used for programming the microcontroller and serial communication with a computer or other device.  
-Enables the Arduino Integrated Development Environment (IDE) on a computer, where users can write and upload code to the board.

7)Reset button

8)Onboard LEDs

9)Boards being compatible with many shields and accessories
