# Arduino Robot Control with Servo and Flame Detection

This Arduino sketch controls a robot chassis using motor drivers and includes functionality for flame detection and alert using a buzzer. Here’s a quick overview:

## Components Used:
- **Servo Motor**: Controls a sensor or actuator (used here for flame detection).
- **Motor Drivers**: Controls two DC motors for movement.
- **Flame Sensor**: Detects flames.
- **Buzzer**: Alerts upon flame detection.
- **Bluetooth**: To control the car

## Commands:
- **F**: Move forward.
- **B**: Move backward.
- **R**: Turn right.
- **L**: Turn left.
- **S**: Stop.
- **V**: Sweep servo from 0 to 180 degrees to detect flames.
  - If flames detected, activates the buzzer for alert.
