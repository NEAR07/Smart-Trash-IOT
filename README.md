# 🗑️ Smart Trash IoT System

The **Smart Trash IoT** system revolutionizes waste management by utilizing IoT technology to monitor and manage waste levels in real time. This system not only detects when a trash bin is full but also sends alerts to waste management personnel or initiates automated waste collection processes, making waste disposal more efficient and effective.

<img src="https://github.com/NEAR07/Smart-Trash-IOT/blob/main/prototype%20picture.jpg" alt="Smart Trash Prototype" width="400">

## 🌟 Features

- **Real-Time Monitoring**: Continuously monitors the fill level of trash bins and sends alerts when they need to be emptied.
- **Automated Waste Collection**: Integrates with automated waste collection systems, triggering them when the bin is full.
- **Multi-Sensor Detection**: Uses various sensors to detect different types of waste (metal, non-metal, organic, non-organic).
- **Smart Lid Control**: Automatically opens and closes the trash lid to reduce odor and prevent pests.

## 🛠️ System Design

<img src="https://github.com/NEAR07/Smart-Trash-IOT/blob/main/System%20Design.jpg" alt="System Design" width="500">

## 🔍 Sensors Used

- **Inductive Proximity Sensor & Infrared Sensor**: Detects metal and non-metal waste.
- **LDR Sensor & Capacitive Proximity Sensor**: Identifies opaque organic waste and transparent non-organic waste.
- **IR Sensor**: Controls the automatic opening and closing of the trash lid.
- **Ultrasonic Sensor**: Measures the trash level, determining when the bin is full and triggering the dispensing of water and chemicals.

## 🔧 Actuators Used

- **Servo Motor**: Acts as a gate, opening and closing based on waste detection. When metal or non-metal waste is detected by the proximity sensors, the servo motor operates to manage the gate accordingly.

## 🎛️ Microcontrollers

- **ESP32**: Handles communication tasks and signals when the trash bin is full.
- **Arduino**: Manages the operations of all sensors and actuators, ensuring seamless system functionality.

## 🚀 Getting Started

### Prerequisites

- Arduino IDE
- ESP32 and Arduino Libraries
- Basic knowledge of IoT and sensor integration

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NEAR07/Smart-Trash-IOT.git

2. Install Dependencies:
   Ensure you have all the required libraries installed in your Arduino IDE.

3. Upload the Code:
   Upload the Arduino and ESP32 code to their respective microcontrollers.

4. Connect the Hardware:
   Set up your sensors and actuators according to the system design.

5. Run the System:
   Power on the system and monitor the real-time data.

## 📊 System Workflow

1. Waste Detection: Sensors detect the type and level of waste.
2. Data Processing: Microcontrollers process the data and determine the necessary action.
3. Lid Operation: The IR sensor triggers the automatic opening/closing of the lid.
4. Level Monitoring: Ultrasonic sensor checks the fill level.
5. Alert & Action: ESP32 sends alerts or triggers automated actions if the bin is full.
