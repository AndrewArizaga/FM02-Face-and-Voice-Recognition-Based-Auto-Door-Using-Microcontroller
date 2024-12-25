FM02: Face and Voice Recognition Based Auto Door Using Microcontroller

Overview
The Face and Voice Recognition Based Auto Door project automates door access using advanced face and voice recognition technologies. By integrating an ESP32 CAM and a serial voice recognition module with an Arduino Uno microcontroller, this project ensures secure and efficient access control, addressing the limitations of traditional motion-based automatic doors.

Key Objectives
- Dual Authentication: Combine face and voice recognition for enhanced security.
- Selective Access: Allow only authorized individuals to open the door.
- Automation: Provide hands-free access for convenience, especially for elderly or disabled users.

Hardware Components
- ESP32 CAM Module: For face detection and recognition.
- Arduino Uno: Central controller for coordinating all hardware.
- Serial Voice Recognition Module & Microphone: To process and verify spoken commands.
- Stepper Motor & Driver: For controlling the door mechanism.
- Power Supply: Separate 5V for logic and 12V for motor operation.

System Workflow
1. Face Recognition: The ESP32 CAM detects and validates a face against a stored database.
2. Voice Command: The microphone captures and verifies an authorized command through the voice recognition module.
3. Door Control: Upon successful authentication, the stepper motor opens/closes the door.

Project Focus
This project emphasizes:
- Practical Implementation: Combining face and voice recognition technologies.
- Efficiency: Ensuring seamless operation with minimal errors.
- Security: Restricting access to authorized individuals only.

Future Applications
- Smart home and workplace automation.
- Enhanced security for restricted access areas.
- Integration into IoT ecosystems for remote control.
