# Artificial Intelligence Based Voice Controlled Scrolling of a Menu on an OLED

## Project Overview

This project presents the design and implementation of a voice-controlled menu navigation system displayed on an OLED screen. The system uses artificial intelligence-based voice recognition to allow users to navigate and scroll through menu options using spoken commands.

The project demonstrates how voice recognition technology can be integrated with embedded systems to enable intuitive human–machine interaction. By using voice commands such as “Go up”, “Go down”, or “Enter”, the user can scroll through menu items displayed on the OLED screen without physical buttons.

The system integrates artificial intelligence, embedded systems, voice processing, and display technology to create a hands-free user interface.

---

## Objectives

The objectives of this project include:

- Design and implement a voice-controlled user interface
- Integrate voice recognition with an embedded system
- Display a scrollable menu on an OLED screen
- Enable hands-free menu navigation using voice commands
- Demonstrate the use of AI-based voice processing in embedded applications

---

## System Architecture

The system consists of several interconnected components responsible for voice recognition, command processing, and display control.

Main subsystems include:

1. Voice input and recognition system
2. Embedded processing unit
3. OLED display interface
4. Menu control logic

System workflow:

User Voice Command → Microphone → Voice Recognition Module → Microcontroller → OLED Display → Menu Navigation

The voice recognition module processes spoken commands and sends corresponding signals to the microcontroller, which updates the displayed menu accordingly.

---

## Hardware Components

The system was developed using the following hardware components:

- Microcontroller (system control unit)- Esp32C3 mini ![c3image](https://github.com/Hackmonstar/AI-Based-Voice-Controlled-OLED-Menu/blob/main/images/ESP32-C3-MINI-image.jpg)
- Microphone for voice input - I2S microphone module ![System Setup]()
- OLED display module - 0.96 inch OLED screen ![System Setup](https://github.com/Hackmonstar/AI-Based-Voice-Controlled-OLED-Menu/blob/main/images/oled%20image.jpg)
- Power supply unit
- Interface circuitry, breadboard and connecting wires

The OLED display provides a compact and energy-efficient interface for visualizing the menu system.

---

## Software Implementation

The system software performs the following key functions:

- Capturing voice input through the microphone
- Processing voice commands using the voice recognition module
- Interpreting recognized commands
- Updating the menu display on the OLED screen
- Implementing menu scrolling logic

The program enables the OLED display to scroll through menu items based on the user’s spoken commands.

---

## Working Principle

The system operates by capturing spoken commands from the user through a microphone. The voice recognition module processes the speech input and identifies predefined commands such as:

- **Go Up** – scrolls the menu upward
- **Go Down** – scrolls the menu downward
- **Enter** – selects/confirms a menu option

Once a command is recognized, the module sends a signal to the microcontroller. The microcontroller interprets the command and updates the OLED display accordingly, causing the menu to scroll or select the desired option.

This creates a hands-free menu navigation system.

---

## Applications

Voice-controlled interfaces have numerous practical applications, including:

- Smart home systems
- Assistive technologies for people with disabilities
- Automotive infotainment systems
- Consumer electronics interfaces
- Industrial control systems
- Human–machine interaction systems

---

## Skills Demonstrated

This project demonstrates knowledge and skills in:

- Artificial intelligence applications
- Voice recognition systems
- Embedded systems programming
- Human–machine interaction design
- Microcontroller interfacing
- OLED display integration

---

## Project Images

Add images of the system setup and OLED interface below.

![System Setup](image1.jpg)

![OLED Menu Display](image2.jpg)

![Hardware Components](image3.jpg)

---

## Demonstration Video

Watch the project demonstration here:

Project Demo:  
https://youtube.com/your-video-link

---

## Future Improvements

Possible improvements to the system include:

- Expanding the voice command vocabulary
- Integrating natural language processing
- Adding multilingual voice support
- Improving recognition accuracy in noisy environments
- Integrating the system into smart devices or IoT platforms

---

## Conclusion

The Artificial Intelligence Based Voice Controlled Scrolling of a Menu on an OLED demonstrates the integration of voice recognition technology with embedded systems to create an intuitive and hands-free user interface. The project highlights the potential of AI-driven voice interaction in modern electronic systems and smart devices.
