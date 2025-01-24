# 4-Legged Emoji Bot

A fun and interactive project for building a 4-legged robot that displays random emojis on an OLED screen. The robot can be controlled via a mobile app using Bluetooth and Arduino Nano. This repository provides all the necessary resources to build and customize the bot.

## Features
- **Arduino Nano-based Control**: The core microcontroller for managing the robot's movements and emoji display.
- **HC-05 Bluetooth Module**: Enables wireless communication with the mobile app.
- **OLED Screen Display**: Displays random emojis to make the robot interactive and engaging.
- **Mobile App Interface**: Control the robot's movements (forward, backward, left, right) via Bluetooth.
- **Easy Replication**: Includes circuit diagrams and PCB design files for seamless reproduction.
- **Customizable**: Modify emoji sets and movement patterns as per your preference.

---

## Repository Structure
```
4_Legged_Emoji_Bot/
├── firmware/           # Arduino code for robot control
├── app/                # Mobile app code (e.g., MIT App Inventor or Flutter)
├── hardware/           # Circuit diagrams and PCB design files
├── assets/             # Emoji sets for the OLED screen
├── docs/               # Assembly and setup instructions
└── README.md           # Project overview and usage guide
```

---

## Getting Started

### Prerequisites
- **Hardware Components**:
  - Arduino Nano
  - HC-05 Bluetooth Module
  - OLED Screen (e.g., SSD1306)
  - Servo Motors (4x for the legs)
  - Power Supply (e.g., 9V battery or USB power)
  - Connecting Wires and Breadboard
  - 3D Printed or Assembled Robot Frame

- **Software Tools**:
  - Arduino IDE
  - MIT App Inventor or Flutter for mobile app development
  - Fritzing or EasyEDA for circuit design

---

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/4_Legged_Emoji_Bot.git
   cd 4_Legged_Emoji_Bot
   ```

2. **Upload Firmware**:
   - Open the `firmware/emoji_bot.ino` file in the Arduino IDE.
   - Select the correct board and port.
   - Upload the code to the Arduino Nano.

3. **Assemble the Hardware**:
   - Follow the instructions in the `docs/hardware_setup.md` to assemble the robot.

4. **Setup the Mobile App**:
   - Use the `app/` folder to create the mobile app.
   - Pair the HC-05 Bluetooth module with your phone.

---

## Usage

1. Power on the robot and ensure the HC-05 module is blinking.
2. Open the mobile app and connect to the HC-05 module.
3. Use the app to control the robot's movements.
4. Watch the OLED screen display random emojis while the robot moves.

---

## Customization

- **Emoji Sets**:
  - Modify the `assets/emojis.h` file to add or change emojis.

- **Movement Patterns**:
  - Adjust the servo motor angles in the `firmware/movement.h` file.

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your branch.
4. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments
- Inspiration from robotics and interactive design projects.
- Open-source tools and libraries that made this project possible.
