# Custom Tilt-Rotor Mechanism for Fixed-Wing VTOL UAV

<img width="710" height="562" alt="image" src="https://github.com/user-attachments/assets/cd17bea5-81da-45fc-baba-9472bd85f15a" />


## Project Overview

This repository contains the design files, documentation, and assembly instructions for a high-accuracy, heavy-duty **Tilt-Rotor Mechanism** engineered specifically for fixed-wing VTOL (Vertical Take-Off and Landing) UAVs. Designed to be deployed as a symmetric pair on a flying wing layout, this mechanism bridges the gap between high-power quadcopter thrust and efficient forward-flight cruising.

The core design philosophy focuses on maximizing deflection accuracy and reducing structural stress on the servo shaft. This is achieved by utilizing an active servo drive on one end and a secondary **623ZZ ball bearing support** on the opposite pivot axis to distribute the mechanical load evenly.

---

## Technical Specifications

* **Target Propulsion System:** 5010 BLDC Motor with 14-inch Propellers
* **Actuator:** MG90S Metal-Geared Micro Servo
* **Load Support Bearing:** 623ZZ Shielded Ball Bearing (3mm ID x 10mm OD x 4mm W)
* **Airframe Integration:** Configured to clamp securely onto a **10mm square Carbon Fiber (CF) boom**
* **Manufacturing Material:** 3D Printed PLA (optimized for rigidity and printing orientation strength)

---

## 💻 CAD Design & Animation

The mechanism was designed from scratch in CAD, optimizing for minimal weight without sacrificing torsional rigidity. The assembly consists of **two primary 3D-printed parts**:

1. **The Base Housing:** Slides over and clamps down onto a 10mm square CF tube. It fully encloses the MG90S servo on one side and features a countersunk M3 screw hole on the opposite flank to seat the load-bearing axle alignment pivot.
2. **The Tilting Arm:** Mounts the 5010 brushless motor. One side interfaces directly with the splined plastic/metal servo horn, while the opposite side retains the 623ZZ bearing, locked rigidly via an M3 screw back to the base housing.

https://github.com/user-attachments/assets/19490eb6-71d6-4aaf-bbe3-709d6d122a36

---

## Build Gallery & Hardware Assembly

### 🧩 Fully Assembled Tilt-Rotor Core
Below is the bare mechanical assembly showing how the two printed PLA parts pivot smoothly across the dual-supported axis. By offloading the bending moments from the 14-inch prop onto the 623ZZ bearing, the MG90S servo is completely isolated from lateral aerodynamic loads, extending its operational life and eliminating slop.

<img width="3208" height="4096" alt="hardware assembly" src="https://github.com/user-attachments/assets/f5b4edbc-75de-44e0-bc92-73a4293bf7cf" />


---

## 📹 Full Propulsion & Deflection Demo

See the mechanism running at full throttle. This demonstration shows zero-slop 50-degree transitions under the gyroscopic and thrust loads produced by the 5010 BLDC motor spinning the massive 14-inch propeller:

▶️ **[Watch the Live Motor & Propeller Testing Video](https://drive.google.com/file/d/1BW0-GQ3EoBWkFSnyJgeziJaLVPEFHEHY/view?usp=sharing)**
