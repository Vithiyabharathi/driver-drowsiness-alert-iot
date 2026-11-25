# Driver's Drowsiness Alert System Using IoT

A real-time safety prototype that monitors driver alertness and triggers instant audio-visual warnings when drowsiness or eye closure is detected.

## Tech Stack & Hardware
- **Software:** Python, OpenCV / Webcam Monitoring
- **Hardware:** NodeMCU (ESP8266), LED Indicator, Buzzer, Breadboard, Resistor

## How It Works
1. Captures real-time video feed through a webcam to monitor eye state.
2. Detects prolonged eye closure indicating drowsiness.
3. Sends a signal to the NodeMCU (ESP8266) to activate the buzzer and LED alert immediately.
