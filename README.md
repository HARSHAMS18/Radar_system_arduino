# Radar System Using Arduino

## Description
This project demonstrates how to build a radar system using an Arduino, an ultrasonic sensor, and a servo motor, with a Processing-based graphical interface to display detected objects.

## Methodology
1. **Hardware Setup**: 
   - Connect an ultrasonic sensor (e.g., HC-SR04) to measure distances and a servo motor to sweep across angles.
   - Link the Arduino to a PC via serial communication.

2. **Arduino Code**:
   - Control the servo motor to sweep from 0° to 180°.
   - Read distance data from the ultrasonic sensor and send it to the PC over the serial port.

3. **Processing Code**:
   - Use Processing to read serial data sent from the Arduino.
   - Parse the received angle and distance data.
   - Render a graphical radar display with real-time updates.

4. **Output**:
   - A radar-like display shows detected objects, indicating their position (angle and distance) relative to the sensor.

## Usage
1. Upload the Arduino sketch to your board.
2. Run the provided Processing script.
3. Observe the radar display updating in real-time based on the sensor data.

## Requirements
- Arduino (Uno, Mega, or similar)
- Ultrasonic sensor (HC-SR04)
- Servo motor
- Processing IDE
- Arduino IDE
- Jumper wires and breadboard

## Future Enhancements
- Increase range and resolution by using advanced sensors.
- Add object classification with machine learning.
- Implement wireless communication to decouple the Arduino and PC.

---
