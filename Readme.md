## Installation
1. Download and install the TimerOne library from the Arduino Library Manager.
2. Upload the sketch to your Arduino board.

## Usage
1. Connect the LM35 sensor and LED to the Arduino as shown in the circuit diagram.
2. Open the serial monitor in the Arduino IDE to view the temperature readings.
3. The LED will blink at different intervals based on the temperature:
   - If the temperature is below the lower threshold, the LED will blink every 250 milliseconds.
   - If the temperature is above the upper threshold, the LED will blink every 500 milliseconds.
