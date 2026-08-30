# automatic-gate-arduino
Automatic Gate System using Arduino Uno, Ultrasonic Sensor and Servo Motor

## 📌 Project Overview

This project demonstrates a simple automatic gate mechanism using
an ultrasonic sensor to detect an approaching object.

When an object comes within 20 cm of the gate, the Arduino commands
the servo motor to open the gate. When no object is detected within
the specified distance, the gate remains closed.

## 🛠️ Components Used

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- Jumper Wires
- Breadboard
- Tinkercad

## ⚙️ Working

1. The ultrasonic sensor continuously measures distance.
2. Arduino calculates the distance using the ultrasonic sensor data.
3. If the detected object is within 20 cm:
   - The servo motor rotates.
   - The gate opens.
4. If no object is detected within the specified range:
   - The servo returns to its original position.
   - The gate remains closed.

## 🔌 Circuit

![Circuit Diagram](<img width="1338" height="867" alt="image" src="https://github.com/user-attachments/assets/91174755-0629-4302-be24-2493b489deac" />
)

## 💻 Code

The Arduino code is available in:

`code/automatic_gate.ino`

## 🎥 Project Demonstration

The project was designed and simulated using Tinkercad.

## 📚 What I Learned

Through this project, I learned:

- Ultrasonic distance sensing
- Distance calculation
- Servo motor control
- Arduino programming
- If-else decision making
- Sensor-to-actuator control
- Basic embedded systems concepts

## 🚀 Future Improvements

- Add an IR sensor for vehicle detection
- Add an LCD/OLED display
- Add RFID-based access control
- Add automatic closing delay
- Add IoT monitoring
- Implement the system using ESP32

## 👨‍💻 Author

Vijay Bijalwan
