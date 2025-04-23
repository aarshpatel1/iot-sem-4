# Assignment - 2 (IoT Devices and Components)

## Answer the short questions:

1. **What is an IoT sensing device?**  
    An IoT sensing device is a hardware component that collects data from the environment (like temperature, humidity, motion) and sends it to other devices or systems for processing.
   <br>

2. **Give two examples of sensors used in IoT applications.**

   - Temperature sensor (e.g., DHT11)
   - Motion sensor (e.g., PIR sensor)
     <br>

3. **What is the role of actuators in an IoT system?**  
    Actuators receive control signals from the IoT system and perform physical actions like turning on a light or adjusting a valve.
   <br>

4. **Name two types of actuators used in IoT.**

   - DC Motor
   - Servo Motor
     <br>

5. **Why is power management important in IoT devices?**  
    Power management is crucial to extend battery life, especially in remote or portable IoT devices, and to ensure consistent and reliable operation.
   <br>

6. **Mention two hardware peripherals of Raspberry Pi.**
   - HDMI port
   - GPIO (General Purpose Input/Output) pins

---

**Resources:**

- [IoT Sensors and Actuators - GeeksforGeeks](https://www.geeksforgeeks.org/introduction-to-sensors-and-actuators-in-iot/)
- [Power Management in IoT - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S1877050921000279)
- [Raspberry Pi Official Documentation](https://www.raspberrypi.com/documentation/)

---

## Answer the long questions:

### **1. Explain the working principles of different types of sensors used in IoT applications**

#### a. **Temperature Sensor (e.g., DHT11, LM35):**

- Measures ambient temperature.
- Works by changing electrical resistance or voltage according to the temperature.
- The microcontroller reads the voltage/resistance to calculate temperature.

#### b. **Humidity Sensor:**

- Measures moisture in the air.
- Uses capacitive or resistive sensing elements.
- Output changes with the change in moisture levels.

#### c. **PIR Motion Sensor:**

- Detects infrared radiation emitted by humans/animals.
- When motion is detected, it sends a high signal to the controller.

#### d. **Ultrasonic Sensor:**

- Measures distance using sound waves.
- Sends an ultrasonic wave and measures the time taken for the echo to return.

#### e. **Light Sensor (LDR):**

- Detects light intensity.
- Resistance decreases with increasing light intensity.

---

### **2. Difference between 8051 and ARM – Microcontroller**

| Feature           | 8051 Microcontroller   | ARM Microcontroller             |
| ----------------- | ---------------------- | ------------------------------- |
| Architecture      | 8-bit                  | 32-bit                          |
| Speed             | Slower                 | High-speed performance          |
| Power Consumption | Higher                 | Lower (optimized for IoT)       |
| Memory            | Limited ROM/RAM        | Large memory support            |
| Instruction Set   | CISC                   | RISC                            |
| Applications      | Basic embedded systems | Advanced embedded & IoT systems |

---

### **3. Explain features of Raspberry Pi**

- **Credit-card-sized single-board computer.**
- **Processor:** ARM-based CPU.
- **Operating System:** Supports Linux-based OS (e.g., Raspberry Pi OS).
- **GPIO Pins:** 40 pins for interfacing sensors and actuators.
- **USB Ports:** Connects keyboard, mouse, or other peripherals.
- **HDMI Output:** For display connection.
- **Camera Interface:** CSI port for connecting a camera.
- **Networking:** Includes Ethernet/Wi-Fi/Bluetooth (in newer models).
- **Storage:** Uses microSD card for OS and data storage.

---

### **4. What are the advantages of using Raspberry Pi in IoT applications?**

- **Cost-effective:** Affordable compared to traditional computers.
- **Compact Size:** Easy to embed in devices and projects.
- **Flexible I/O:** GPIO allows interfacing with multiple sensors/actuators.
- **Built-in Networking:** Supports internet connectivity (Wi-Fi/Ethernet).
- **Open Source Software:** Wide community support and software availability.
- **Multiple Use Cases:** Suitable for prototyping, automation, smart devices.

---

### **5. Explain Actuators in IoT and write advantages and disadvantages**

#### **Definition:**

Actuators are devices that convert electrical signals from a microcontroller into physical action (e.g., movement, turning on/off a device).

#### **Types of Actuators:**

- **DC Motors:** Produce rotational motion.
- **Servo Motors:** Controlled precise movement.
- **Relays:** Electrically controlled switches.
- **Solenoids:** Convert electrical energy into linear motion.

#### **Advantages:**

- Enable physical interaction with the environment.
- Can be automated and remotely controlled.
- Compatible with various microcontrollers and IoT platforms.

#### **Disadvantages:**

- May require additional power supply.
- Wear and tear over time.
- Complex control in some cases (e.g., servo tuning).

---

**Resources:**

- [Sensors in IoT - GeeksforGeeks](https://www.geeksforgeeks.org/introduction-to-sensors-and-actuators-in-iot/)
- [8051 vs ARM - Embedded Systems](https://circuitdigest.com/article/difference-between-8051-and-arm-microcontrollers)
- [Raspberry Pi Features - RaspberryPi.com](https://www.raspberrypi.com/products/)
- [Actuators in IoT - ScienceDirect](https://www.sciencedirect.com/topics/engineering/iot-actuator)

---

<p align='right'><strong>- Aarsh  Patel</strong></p>
