# wireless-bluetooth-display-with-buzzer
The Wireless Message Display System offers a practical solution for wirelessly receiving and displaying messages using an Arduino microcontroller 
and a wireless module. The system's ability to communicate wirelessly provides flexibility in various applications, such as remote control systems 
and also value detection systems in a particular Device or Embedded System Device.

# Circuit Design
<img width="686" alt="Screenshot 2023-09-17 at 12 40 31 AM" src="https://github.com/ananta1579/wireless-bluetooth-display-with-buzzer/assets/64258573/454b9bc9-b89f-417a-a132-8fec2e1c77ea">

# Project Image

<img width="533" alt="Screenshot 2023-09-17 at 12 40 49 AM" src="https://github.com/ananta1579/wireless-bluetooth-display-with-buzzer/assets/64258573/4a6b3b4d-933e-467d-9ba7-fad5cc256b9e">
<img width="350" alt="Screenshot 2023-09-17 at 12 40 58 AM" src="https://github.com/ananta1579/wireless-bluetooth-display-with-buzzer/assets/64258573/17218125-ff11-4242-9aa6-d50e365c24e7">


# Software Libraries
The project utilizes the following libraries:
* LiquidCrystal: This library provides functions to control and manipulate the LCD display.
* SoftwareSerial: This library enables software-based serial communication on specific digital pins of the Arduino, allowing communication with the wireless module.

# Installation

Hardware Setup:

Components and Connections:

Ensure you have all the necessary hardware components, including the Arduino board, LCD display, Bluetooth module (if used), buzzer, LED, connecting wires, breadboard, resistors, and a power source (USB or external adapter).

Physical Connections:

Connect the hardware components according to the circuit diagram used in your project.
Double-check your connections to make sure they match the pin configurations in your source code.
Provide power to the Arduino board through the USB cable or an external power source.
Software Installation:

Arduino IDE:

Install the Arduino IDE on your computer if you haven't already. You can download it from the official Arduino website (https://www.arduino.cc/en/software).
Libraries:

Open the Arduino IDE.
Go to the "Sketch" menu, then select "Include Library" and choose "Manage Libraries."
Search for and install the following libraries if you haven't already:
"LiquidCrystal" for controlling the LCD display.
"SoftwareSerial" for software-based serial communication.
Upload the Code:

Copy and paste the provided source code into your Arduino IDE.
Ensure that the Arduino board selected in the "Tools" menu matches the one you're using (e.g., Arduino Uno).
Click the "Upload" button (right arrow icon) to compile and upload the code to your Arduino board.
Serial Monitor:

Open the Serial Monitor in the Arduino IDE by clicking on the magnifying glass icon in the upper right corner.
Set the baud rate in the Serial Monitor to 9600 (the same as in your code).
Power On:

Power on the hardware setup if you haven't already.
Testing:

After uploading the code and powering on the system, you should see a message on the LCD display indicating that it's a "WIRELESS MESSAGE DISPLAY."

The system will wait for incoming messages through the Bluetooth module or the configured serial connection.

You can send messages to the system through your chosen communication method (Bluetooth or serial). The messages should appear on the LCD display, and the LED should blink when a new message arrives.
