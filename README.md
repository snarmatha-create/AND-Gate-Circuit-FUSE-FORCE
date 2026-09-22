# AND LOGIC GATE CIRCUIT USING 9V BATTERY

## DESCRIPTION
An interactive digital electronics project that implements a two-input AND logic gate on a prototype dot-board using physical switches to control a green LED.

## MATERIALS REQUIRED
* GREEN LED
* 9V BATTERY
* BATTERY SNAP CONNECTOR
* TACTILE PUSH-BUTTON SWITCHES (2x)
* RESISTOR
* PROTOTYPING DOT-BOARD (PERFBOARD)
* CONNECTING WIRES & SOLDER

## PROBLEM STATEMENT
In automated machinery and safety systems, machines often need to make sure multiple conditions are met at the exact same time before turning on. This circuit solves the problem of building a reliable, hardware-enforced safety switch that ensures an output device cannot turn on accidentally if only one button is pressed or bumped.

## PROCEDURE
1. Place the components onto the prototyping dot-board layout.
2. Wire the two push-button switches in a series configuration.
3. Connect the series switch network to the resistor and LED.
4. Attach the 9V battery snap connector to power the main lines.
5. Press both buttons simultaneously to test circuit operation.

## WORKING
The 9V battery supplies DC power to the circuit. Because the switches are wired in a series layout, electricity is blocked if either button is open. When both buttons are pressed together, the circuit path closes, allowing current to flow through the resistor and illuminate the green LED.

## PROJECT IMAGES

### 1. Hardware Overview Top-Down Layout
![Hardware Overview]()

### 2. Physical Circuit Test (Both Buttons Pressed)
![Circuit Test]()

## NOTES
* Connect the LED with the correct polarity.
* Use a resistor to limit current and prevent burning out the LED.
* Change the push-buttons to toggle switches for hands-free operation.
* Place the board inside an enclosure to protect the exposed bottom wires.
* Move the design to a custom printed circuit board (PCB) to eliminate messy hand-soldering.
*
