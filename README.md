# Traffic Control System using Arduino

Simulated traffic signal using Arduino, cycling Red, Yellow, and Green LEDs to mimic real-world traffic light behavior.

## Components
- Arduino Uno
- Red, Yellow, Green LEDs
- 3x 220Ω resistors
- Breadboard & jumper wires

## Pin Connections
| LED    | Pin |
|--------|-----|
| Red    | 13  |
| Yellow | 12  |
| Green  | 11  |

## How It Works
1. Red ON – 5s (stop)
2. Yellow ON – 2s (caution)
3. Green ON – 5s (go)

Loops continuously using `digitalWrite()` and `delay()`.

## Simulation
Built and tested on [Wokwi](https://wokwi.com).

## Usage
1. Open `sketch.ino` in Arduino IDE or Wokwi
2. Wire LEDs as shown above
3. Upload and run

## Author
Nagur425
