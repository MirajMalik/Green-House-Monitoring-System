Greenhouse Monitoring and Control System 

An Arduino-based embedded system that monitors and controls environmental parameters inside a greenhouse, ensuring optimal plant growth conditions.

## Features
-  Temperature and Humidity Monitoring using DHT11
-  Soil Moisture Detection
-  Light Detection using LDR
-  Automatic Water Pump Control
-  Fan Control for Overheat Protection
-  Light Control Based on Brightness
-  Real-time LCD Display (I2C 16x2)
-  Servo Motor (for window/vent adjustment or door)

## Hardware Used
- Arduino Uno
- DHT11 Temperature and Humidity Sensor
- Soil Moisture Sensor (Analog)
- LDR (Light Dependent Resistor)
- Relay Module (For pump and fan)
- Light (LED/Bulb)
- Servo Motor
- 16x2 I2C LCD Display
- Jumper Wires, Breadboard, Power Supply




## Working Principle

- The system uses sensors to continuously read:
  - **Temperature & Humidity** from DHT11
  - **Soil moisture** via analog pin
  - **Light intensity** using LDR

- Based on readings:
  - Turns on **fan** if temperature is high
  - Activates **water pump** if soil is dry
  - Switches **light** on/off based on LDR reading
  - Controls **servo motor** for window/vent

- Data is printed to the **LCD display** and **Serial Monitor**.


## How to Use

1. Wire the components as per the circuit diagram.
2. Upload the code to your Arduino Uno using the Arduino IDE.
3. Monitor readings on the LCD and Serial Monitor.
4. Watch automation in action!

## License

MIT License
---

### Connect with Me

- 👨‍💻 [GitHub Profile](https://github.com/MirajMalik)
- 🌐 [LinkedIn Profile](https://www.linkedin.com/in/tarek-abdullah-miraj-1302122b4/)


