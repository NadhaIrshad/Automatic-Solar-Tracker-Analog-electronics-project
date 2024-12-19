# Analog-electronics-project

# Automatic Solar Tracker

Welcome to the repository of the **Automatic Solar Tracker**, a project aimed at maximizing the efficiency of photovoltaic (PV) systems by maintaining optimal alignment between solar panels and the sun throughout the day. This innovative system combines analog control techniques and sustainable design principles, making it a cost-effective and eco-friendly solution for solar energy optimization.

---

## 🌟 Project Overview

Solar power is one of the most sustainable energy sources, especially in sun-rich regions. However, fixed solar panels often fail to capture maximum sunlight throughout the day due to the changing position of the sun. The **Automatic Solar Tracker** addresses this limitation by dynamically adjusting the orientation of solar panels using a single-axis tracking mechanism.

The system incorporates:

- **Light-dependent resistors (LDRs):** For detecting sunlight intensity.
- **PID controller:** Implemented using operational amplifiers for precise alignment.
- **Motor driver:** Ensures smooth panel movement.
- **Pulse-Width Modulation (PWM):** Controls the motor speed.

---

## ⚙️ Features

1. **Sunlight Sensing:** Measures light intensity using LDRs to detect the sun's position.
2. **PID Control:** Maintains precise alignment through Proportional-Integral-Derivative adjustments.
3. **Motor Control:** Adjusts panel orientation efficiently.
4. **Eco-Friendly Design:** The enclosure combines wood and 3D-printed PLA for sustainability and durability.
5. **Compact Design:** A two-layer PCB integrates all electronic components seamlessly.

---

## 📐 System Design

### Block Diagram


![block diagram](https://github.com/user-attachments/assets/2c3c2ce4-9e5a-419a-b204-1c146377f358)

The system architecture consists of sunlight sensors, a PID controller, motor control circuitry, and a robust enclosure.

### Circuitry

- **Error Signal Generation:** Processes the voltage difference between LDRs to determine misalignment.
- **PWM Generation:** Controls motor speed to correct panel orientation.
- **Motor Driver Circuit:** Drives the motors responsible for panel adjustments.

### Breadboard Implementation
![breadboard](https://github.com/user-attachments/assets/87787f1e-07e4-4d6c-b4c4-04740c24582d)


### Simulation and Testing

Multisim simulations validated the functionality of the PID controller and PWM generation. Real-world testing confirmed enhanced solar energy capture.


![square waveform](https://github.com/user-attachments/assets/f2b3a557-993f-4770-802c-34736111e255)
![triangular waveform](https://github.com/user-attachments/assets/96d8f53c-e76c-45a4-beef-a2565c23d5b0)
![PWM signal](https://github.com/user-attachments/assets/e569ed30-8205-4bb9-af19-55fac89da6b5)


---

## 🖼️ Project Images

1. **System Prototype**
   ![final_product](https://github.com/user-attachments/assets/1e0297f5-0b4b-425c-8695-d4452fc2bd68)

2. **PCB Design**

![schematic](https://github.com/user-attachments/assets/b233b9ca-d73d-46f9-b074-293748796eea)
![top](https://github.com/user-attachments/assets/f9da1cc3-3187-4331-a3df-2279a540527c)
![bottom](https://github.com/user-attachments/assets/64788070-0f3b-46a8-9334-4b4ba509182e)
![3d](https://github.com/user-attachments/assets/550e6339-fa14-4ae6-874f-b8eed396f190)


![PCB Schematic](https://github.com/user-attachments/assets/c9c3af36-9f07-4afc-9763-69aa8f4a52f6)

![3D layout](https://github.com/user-attachments/assets/4a6032be-3c6b-468c-8eef-86c98e8ce1d6)

![top layer]([https://github.com/user-attachments/assets/9bdabce6-73c3-45c3-965d-e9513e4b9cd7](https://github.com/Demitha-Manawadu/Automatic-Solar-Tracker-Analog-electronics-project/blob/main/PCB%20design/images/top%20layer.png))

![bottom layer](https://github.com/user-attachments/assets/94a464ba-6ec2-4b7e-8b50-5c37dafc8785)

4. **Enclosure**

![wood assembly](https://github.com/user-attachments/assets/5a8ca8b4-f118-46fa-b1df-599e9ac69fa6)

---

## 📋 Specifications

- **Controller:** Analog PID using operational amplifiers.
- **Sensors:** Light-Dependent Resistors (LDRs).
- **Power Source:** Solar panel output.
- **Enclosure Materials:** Wood and PLA.

---

## 🔧 Assembly

The assembly involves integrating electronic components onto a compact PCB, crafting the enclosure, and configuring the system for dynamic solar tracking.
![final assembly](https://github.com/user-attachments/assets/efc6c952-43a4-444c-a74f-858255f2c839)


---

## 🚀 Future Improvements

1. Upgrade to a dual-axis tracking system for enhanced efficiency.
2. Transition from analog to digital control for better accuracy and flexibility.
3. Integration with IoT for remote monitoring and control.

---

## 🤝 Acknowledgments

We thank the Department of Electronic & Telecommunication Engineering at the University of Moratuwa for providing the resources and guidance necessary for this project.

---


