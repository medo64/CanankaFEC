[CAN Bus Framework Expansion Card](https://medo64.com/cananka/)
===============================================================

Cananka allows for the computer control of a CAN bus. The control of device is
possible via serial port (SLCAN compatible, Windows/Linux) or via SocketCAN
network driver (Linux).


## CAN Bus Pinout

To connect to this board, one has to use a 4-pin JST XH connector. The following
table represents the pinout, pin 1 being on the left as looking into the
expansion card.

| # | Ref   | Description                     |
|--:|:-----:|---------------------------------|
| 1 | GND   | Ground connection               |
| 2 | CAN L | CAN low-side                    |
| 3 | CAN H | CAN high-side                   |
| 4 | V+    | Not connected                   |

As power consumption is low, wires can be almost any AWG. I would recommend
using 24 AWG wire 0.25 mm² as they allow for greater compatibility with other
connectors.


## LEDs

Left LED will blink on UART communication with computer (both sending toward and
receiving data from computer).

Right LED will blink on CAN bus activity.


## Other repositories

The following hardware version are also available:
* [Full](https://github.com/medo64/Cananka) (isolated and in the case)
* [Framework Expansion Card](https://github.com/medo64/CanankaFEC) (non-isolated, in framework expansion card format)
* [HAT](https://github.com/medo64/CanankaHAT) (intended for Raspberry Pi)

The following additional repositories might be of interest:
* [Firmware](https://github.com/medo64/Cananka.Firmware)
* [Protocol](https://github.com/medo64/Cananka.Firmware/blob/main/PROTOCOL.md)
* [Test software](https://github.com/medo64/Cananka.Software)


---
*You can check my blog and other projects at [www.medo64.com](https://www.medo64.com/electronics/).*
