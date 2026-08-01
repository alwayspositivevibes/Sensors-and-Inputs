# 📡 Electronics Fundamentals: Sensors & Inputs

Welcome to the **Sensors and Inputs** module of the *Electronics Fundamentals* series! 🚀

This repository brings together a collection of custom printed circuit board (PCB) designs and hardware projects focused on capturing real-world environmental signals—such as distance, infrared light reflection, and ambient light levels—and translating them into actionable electronic outputs.

All schematics and board layouts in this series are designed using **LibrePCB**.

---

## 🧰 Included Projects

### 1. 🦇 [Ultrasonic Obstacle Detector](https://github.com/alwayspositivevibes/Ultrasonic-Obstacle-Detector)
* **Description:** A 5V distance-sensing circuit that interfaces with an HC-SR04 ultrasonic module. It uses an NPN transistor switch (`BC547`) triggered by the sensor's echo signal to activate a status LED.
* **Key Components:** HC-SR04 Module, BC547 NPN Transistor, 1kΩ Resistor, 330Ω Resistor, LED, 2-pin Power Header.
* **Concepts Covered:** High-frequency pulse timing interfaces, transistor switching, current-limiting logic.

---

### 2. 🚨 [IR Obstacle Detector](https://github.com/alwayspositivevibes/IR-Obstacle-Detector)
* **Description:** An active optical proximity sensing board utilizing an Infrared (IR) emitter and photodiode pair to detect objects in close proximity based on light reflection.
* **Key Components:** IR LED Emitter, Photodiode / Phototransistor, Op-Amp Comparator / Transistor Gain Stage, Indicator LED.
* **Concepts Covered:** Optical reflection, signal comparison, analog input thresholding.

---

### 3. 🌙 [LDR Automatic Night Lamp](https://github.com/alwayspositivevibes/LDR-Automatic-Night-Lamp)
* **Description:** An automated ambient light detection circuit using a Light Dependent Resistor (LDR) configured in a voltage divider network to automatically switch on a light indicator when room light drops below a threshold.
* **Key Components:** LDR (Photoresistor), Biasing Resistor Network, Transistor / Switching Driver, Output LED.
* **Concepts Covered:** Resistance variation under light intensity, voltage dividers, threshold-based automated switching.

---

## 🛠️ Design Standards & Specifications

* **EDA Tool:** [LibrePCB](https://librepcb.org/)
* **Operating Voltage:** 5V DC
* **Trace Width Standards:** 
  * `0.8 mm` for Power ($V_{CC}$) and Ground ($\text{GND}$)
  * `0.5 mm` for Signal Routing
* **Routing Geometry:** 45° trace bends, localized ground copper pours

---

## 🏷️ Repository Topics / Tags

`librepcb` • `pcb-design` • `electronics-fundamentals` • `sensors` • `hardware` • `hc-sr04` • `ir-sensor` • `ldr` • `schematics`
