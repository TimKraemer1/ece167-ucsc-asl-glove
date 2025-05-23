# The Sensational Sensors

## ASL Character Detection Glove

This repository contains the code and resources for our **ECE 167: Sensors and Sensing Technology** final project—a glove designed to detect American Sign Language (ASL) characters. The project serves as a proof of concept for future work in ASL parsing and translation, leveraging a **PIC32 Uno32 microcontroller**.

---

## 📂 Repository Structure

- `ASL_Glove_Flex_Test.X/`  
  Contains all the embedded code running on the Uno32.  
  - The main source file: `Flexion_Test.c`  
  - Compilation via MPLAB X IDE or `make` in a terminal  
  - Uses the custom `Node` library for tree data structure management  

- `Common/`  
  Custom library files (`Node.h/.c` and others) providing functions and data structures to build and interact with the detection tree. This library is automatically included in the build process and typically requires no direct interaction.

- `matlab/`  
  MATLAB scripts for glove calibration, including comparisons between filtered and unfiltered flex sensor data.

- `Progress Images/`  
  Images documenting progress on the tree traversal algorithm and graphs generated from MATLAB calibration data.

---

## 🛠️ Development Environment

- **Microcontroller:** PIC32 Uno32  
- **IDE:** MPLAB X  
- **Compilation:** IDE “Make and program device” feature or terminal `make` command  
- **Calibration & Analysis:** MATLAB

---

## 🎯 Project Goals

- Detect ASL characters through flex sensor data captured by a glove  
- Use a tree-based algorithm to identify character gestures  
- Provide a foundation for future ASL translation systems

---

Feel free to explore the code, calibration scripts, and documentation for more details on implementation and performance.

