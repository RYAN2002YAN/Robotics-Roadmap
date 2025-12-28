# Robotics-Roadmap
# From Finance to Robotics: My Self-Study Journey

**Author:** Ryan
**Background:** Financial Management / Quantitative Social Science
**Target:** Robotics Engineering (M.S. & Ph.D.)
**Status:** 🚀 In Progress (Preparing for WPI/MIT)

> "Transitioning from analyzing market volatility to controlling mechanical instability."

This repository documents my lecture notes, code implementations (C++/Python), and problem sets based on the **MIT OpenCourseWare (OCW)** curriculum. This roadmap is designed to fulfill the prerequisite requirements for a top-tier Robotics Master's program.

---

## The Engineering Roadmap

### Phase 1: The Mathematical Engine (Math Prerequisites)
*Building the theoretical foundation for kinematics and system dynamics.*

**1. Linear Algebra** (Crucial for Rotation Matrices & State Estimation)
* **Course:** [MIT 18.06: Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
* **Instructor:** Prof. Gilbert Strang
* **My Focus:**
    * [ ] Matrix Multiplication & Inverse (Coordinate Transformations)
    * [ ] Eigenvalues & Eigenvectors (System Stability Analysis)
    * [ ] SVD (Singular Value Decomposition)
    * [ ] *Project:* Python/NumPy implementation of rotation matrices.

**2. Differential Equations** (Crucial for Control Systems)
* **Course:** [MIT 18.03: Differential Equations](https://ocw.mit.edu/courses/18-03-differential-equations-spring-2010/)
* **Instructor:** Prof. Arthur Mattuck
* **My Focus:**
    * [ ] First & Second Order Linear Equations (Modeling Mass-Spring-Damper systems)
    * [ ] System Step Response (Overdamped vs. Underdamped)
    * [ ] Laplace Transform (Transfer Functions)

---

### Phase 2: The Programming Core (CS Prerequisites)
*Mastering the language of Robotics (C++) and efficient data processing.*

**3. Introduction to C++** (The Industry Standard)
* **Course:** [MIT 6.096: Introduction to C++](https://ocw.mit.edu/courses/6-096-introduction-to-c-january-iap-2011/)
* **My Focus:**
    * [ ] Memory Management (Pointers & References)
    * [ ] Object-Oriented Programming (Classes for Robot Components)
    * [ ] Standard Template Library (STL)

**4. Algorithms & Data Structures** (For Path Planning & SLAM)
* **Course:** [MIT 6.006: Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/)
* **Instructor:** Prof. Erik Demaine
* **My Focus:**
    * [ ] Sorting & Searching
    * [ ] Graph Algorithms (BFS/DFS/Dijkstra for Path Planning)
    * [ ] Dynamic Programming

---

### Phase 3: The Physical World (EE Prerequisites)
*Understanding the hardware layer: Sensors, Actuators, and Circuits.*

**5. Circuits and Electronics**
* **Course:** [MIT 6.002: Circuits and Electronics](https://ocw.mit.edu/courses/6-002-circuits-and-electronics-spring-2007/)
* **Instructor:** Prof. Anant Agarwal
* **My Focus:**
    * [ ] Op-Amps (Signal Conditioning for Sensors)
    * [ ] First-Order RC Circuits (Low-pass Filters for Noise Reduction)
    * [ ] MOSFETs (Motor Drive Logic)
    * [ ] *Tool:* LTSpice Simulation.

---

### Phase 4: Robotics & Control (Core Competency)
*The intersection of Math, CS, and EE. The brain of the robot.*

**6. Introduction to Robotics** (Kinematics & Dynamics)
* **Course:** [MIT 2.12: Introduction to Robotics](https://ocw.mit.edu/courses/2-12-introduction-to-robotics-fall-2005/)
* **My Focus:**
    * [ ] Forward & Inverse Kinematics
    * [ ] Jacobian Matrix
    * [ ] Robot Dynamics (Lagrangian Formulation)

**7. Feedback Control Systems** (The Logic behind Stabilization)
* **Course:** [MIT 16.30: Feedback Control Systems](https://ocw.mit.edu/courses/16-30-feedback-control-systems-fall-2010/)
* **My Focus:**
    * [ ] PID Control (Tuning for Neuro-Stabilizer Spoon)
    * [ ] State-Space Representation
    * [ ] Root Locus Analysis & Stability Margins

---

### Phase 5: The Holy Grail (Advanced Goal)
*Targeting MIT's cutting-edge dynamic robotics research.*

**8. Underactuated Robotics**
* **Course:** [MIT 6.832: Underactuated Robotics](https://ocw.mit.edu/courses/6-832-underactuated-robotics-spring-2009/)
* **Instructor:** Prof. Russ Tedrake (CSAIL)
* **Status:** *Future Goal for PhD Preparation*

---

## 🛠️ Applied Project: Neuro-Stabilizer
**A Low-Cost Active Tremor Cancellation Spoon**
Applying the above theories to build a real-world medical device.
- **Microcontroller:** STM32 (C++ / HAL)
- **Control:** PID Loop (Theory from MIT 16.30)
- **Sensor Fusion:** Complementary Filter (Math from MIT 18.06)
- [View Project Code & Demo Log](./Neuro-Stabilizer-Project)
