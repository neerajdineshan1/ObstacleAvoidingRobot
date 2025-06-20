# 🤖 Obstacle Avoiding Robot (Arduino)

This is an Arduino-based robot that detects and avoids obstacles using an ultrasonic sensor.

## Components

- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- L298N Motor Driver
- 2x DC Motors with wheels
- Chassis & Caster Wheel
- Battery Pack
- Jumper Wires

## Working

- Uses HC-SR04 to measure distance
- If an object is within 20cm, it stops, backs up, and turns
- Continues forward otherwise

## Wiring Diagram

![Circuit Diagram](images/circuit_diagram.png)

## How to Use

1. Connect all components as per the diagram
2. Upload the code to Arduino
3. Power the robot and it will start moving autonomously

## License

MIT

