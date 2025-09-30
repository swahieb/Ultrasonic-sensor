# ultrasonic_sensor 🔊📡

An Arduino project that uses an **HC-SR04 ultrasonic sensor** and an **active buzzer** to create a simple distance-based alarm.  
Whenever an object comes closer than **18 cm**, the buzzer activates to alert you — just like the parking sensors you see in cars 🚗.

---

## 📖 Description
The ultrasonic sensor emits an inaudible sound wave and measures the time it takes for the echo to bounce back from a nearby object.  
Using this time, the Arduino calculates distance. If the distance is below the threshold (set to 18 cm), the buzzer on pin D11 turns on. Otherwise, it stays silent.  

You can also view the real-time distance readings in the Arduino IDE Serial Monitor at **9600 baud**.

---

## ⚙️ Components
- Arduino Uno R3 (or compatible board)  
- HC-SR04 Ultrasonic Sensor  
- Active Buzzer (2-pin)  
- jumper wires  

---

## 🔌 Pin Connections
- **TRIG → D6**  
- **ECHO → D7**  
- **BUZZER → D11 (long leg +)**  
- **VCC → 5V**  
- **GND → GND**  

---

## 🖥️ How to Run
1. Clone this repo or download the sketch.  
2. Open `ultrasonic_sensor/ultrasonic_sensor.ino` in Arduino IDE.  
3. Select your correct **Board** and **Port**.  
4. Upload the sketch.  
5. Open Serial Monitor at **9600 baud** to see distance readings.  





