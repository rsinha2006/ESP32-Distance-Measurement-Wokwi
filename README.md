# ESP32 Ultrasonic Distance Alarm using Wokwi

This project demonstrates distance measurement using an HC-SR04 Ultrasonic Sensor with an ESP32 in the Wokwi simulator. The system activates an LED and a buzzer when the measured distance exceeds 100 cm.

## Components
- ESP32 DevKit C V4
- HC-SR04 Ultrasonic Sensor
- LED
- Buzzer

## Working
- The ESP32 sends a trigger pulse to the HC-SR04 ultrasonic sensor.
- The sensor measures the distance by calculating the time taken for the echo signal to return.
- The measured distance is displayed on the Serial Monitor in both centimeters (cm) and inches (in).
- If the measured distance is greater than **100 cm**:
  - LED turns **ON**
  - Buzzer turns **ON**
- If the measured distance is **100 cm or less**:
  - LED turns **OFF**
  - Buzzer turns **OFF**

## Files
- `sketch.ino` 
- `diagram.json`

## Simulation
https://wokwi.com/projects/468790792472031233

## Output

- Displays distance in the Serial Monitor.
- LED and buzzer activate when the measured distance is greater than **100 cm**.
- Real-time distance can be adjusted using the HC-SR04 distance slider in Wokwi.

## Author

Ernet
