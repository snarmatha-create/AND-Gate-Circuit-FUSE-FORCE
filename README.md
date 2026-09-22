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

## TRUTH TABLE<img width="1600" height="1200" alt="Physical circuit" src="https://github.com/user-attachments/assets/cfe6c2f0-790e-48a7-8aef-18b09be7d99b" />
<img width="1204" height="1600" alt="Circuit overview" src="https://github.com/user-attachments/assets/0d705e6e-500a-45cf-8177-f2bd5e53dd43" />


| Button 1 | Button 2 | LED Status |
| :---: | :---: | :---: |
| Released (0) | Released (0) | OFF (0) |
| Released (0) | Pressed (1) | OFF (0) |
| Pressed (1) | Released (0) | OFF (0) |
| **Pressed (1)** | **Pressed (1)** | **ON (1)** |

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
![Hardware Overview](YOUR_LINK_FOR_IMAGE_2_HERE)

### 2. Physical Circuit Test (Both Buttons Pressed)
![Circuit Test](YOUR_LINK_FOR_IMAGE_1_HERE)

## NOTES
* Connect the LED with the correct polarity.
* Use a resistor to limit current and prevent burning out the LED.
* Change the push-buttons to toggle switches for hands-free operation.
* Place the board inside an enclosure to protect the exposed bottom wires.
* Move the design to a custom printed circuit board (PCB) to eliminate messy hand-soldering.
*
