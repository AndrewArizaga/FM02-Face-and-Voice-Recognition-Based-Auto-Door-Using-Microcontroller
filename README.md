# FM02: Face and Voice Recognition Based Auto Door Using Microcontroller

## Overview
The **Face and Voice Recognition Based Auto Door** project is a cutting-edge solution to automate door access using advanced face and voice recognition technologies. By integrating the ESP32 CAM module and a serial voice recognition module with an Arduino Uno microcontroller, this project ensures secure, efficient, and selective access control, overcoming the limitations of traditional motion-based systems.

---

## Key Objectives
- **Dual Authentication:** Combine face and voice recognition for enhanced security.
- **Selective Access:** Restrict access to only authorized individuals.
- **Hands-Free Automation:** Provide convenient, hands-free access, especially for the elderly or disabled.

---

## Hardware Components
- **ESP32 CAM Module:** Captures and recognizes facial features in real-time.
- **Arduino Uno:** Acts as the central controller, coordinating hardware operations.
- **Serial Voice Recognition Module & Microphone:** Captures and verifies spoken commands for voice authentication.
- **Stepper Motor & Driver:** Controls the automated door mechanism.
- **Power Supply:** Provides 5V for logic circuits and 12V for the stepper motor.

---

## System Workflow
1. **Face Recognition:**  
   The ESP32 CAM captures and validates the user's face against a stored database of authorized profiles.
2. **Voice Command:**  
   The microphone captures the user's voice command, which is verified by the serial voice recognition module.
3. **Door Control:**  
   Upon successful dual-layer authentication, the Arduino Uno triggers the stepper motor to open the door. The door closes automatically after a timeout or upon receiving a "close" command.

---

## Project Focus
This project emphasizes:
- **Practical Implementation:** Integration of face and voice recognition technologies with embedded systems.
- **Efficiency:** Ensuring seamless and reliable operation with minimal errors.
- **Security:** Providing robust access control to protect against unauthorized use.

---

## Future Applications
- **Smart Home Integration:** Automate home entry with advanced security measures.
- **Workplace Automation:** Enhance security for restricted access areas.
- **IoT Ecosystem:** Enable real-time remote control and monitoring through IoT connectivity.

---

## How to Use
1. Approach the door; the system will initiate **face recognition**.
2. Speak the predefined **voice command** for authentication.
3. If both steps are successful, the door will open automatically.

---

Feel free to let me know if further enhancements are needed or if you'd like to add an additional section!
