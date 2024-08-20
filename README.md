# SMART TRASH IoT
The Smart Trash IoT system is designed to improve waste management efficiency by integrating IoT technology to monitor and manage waste levels in trash bins. The system can automatically detect when a bin is full and needs to be emptied, sending real-time alerts to waste management personnel or even triggering automated waste collection processes.

## Sensors used
- Inductive Proximity Sensor and Infrared Sensor: Detects metal and non-metal waste.
- LDR Sensor and Capacitive Proximity Sensor: Detects opaque organic waste and transparent non-organic waste.
- IR Sensor: Automatically opens and closes the trash lid.
- Ultrasonic Sensor: Detects the trash level, indicating whether the bin is full or not. It also triggers the automatic dispensing of water and chemicals.

## Actuators used
Servo Motor: Acts as a gate, opening and closing when waste is detected. If the inductive proximity sensor and infrared sensor detect metal or non-metal (organic or non-organic) waste, the servo motor will operate to open or close the gate.

## Microcontrollers
- ESP32: Manages communication and indicates when the trash bin is full.
- Arduino: Controls all sensors and actuators.
