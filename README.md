🔧  PCB Design Project
This project is a 2-layer PCB design made to interface with a USB to TTL module and a microcontroller (ATmega32). The main goal of the project is to allow easy programming and testing of the ATmega32 using a simple USB connection and a stable power source.

🎯 Main Features:
Microcontroller: ATmega32

USB Interface: Connected through a 1x5 pin connector to any USB to TTL module

Programming: Code is burned into the ATmega32 using USB to TTL

Standalone Operation: After burning the code, the system can run independently using output power

🔌 Power Management:
A 7805 voltage regulator is used to protect the microcontroller in case the user connects a power supply higher than 5V

A Power LED is connected to show that the microcontroller is powered on

💡 Testing and Indicators:
3 LEDs are connected to Port D, pins 2, 3, and 4

These LEDs are used for testing the microcontroller's output and functionality

🔄 Connectivity:
4 x 8-pin sockets are added to connect the microcontroller’s 4 ports (Port A, B, C, D)

1 x 5-pin connector connects the USB to TTL module to the microcontroller (for RX, TX, VCC, GND, and RESET if needed)

⏱ Clock:
A 16 MHz crystal oscillator is used for accurate timing

2 capacitors are connected with the crystal to stabilize the clock signal

