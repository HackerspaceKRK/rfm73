rfm73
=====

This is a library for the Arduino. Designed originaly to work with the Radioduino.

## Connecting RFM73 to Arduino

| RFM73 pin | signal | Arduino Uno | Arduino Mega |
| --------- | ------ | ----------- | ------------ |
| 1         | GND    | GND         | GND          |
| 2         | VDD    | 3.3V        | 3.3V         |
| 3         | CE     | 8           | 8            |
| 4         | CSN    | 10          | 53           |
| 5         | SCK    | 13          | 52           |
| 6         | MOSI   | 11          | 51           |
| 7         | MISO   | 12          | 50           |
| 8         | IRQ    | 2           | 2            |

## Installation

If you need help installing this library take a look at this page:
http://arduino.cc/en/Guide/Libraries

## Schematics

Eagle boardfiles and schematic are available here: https://github.com/heye/radioduino
