# digestive_system_demostrator_using_arudinouno

# 🧬 Digestive System Demonstrator

## 📌 About the Project

The **Digestive System Demonstrator** is an interactive educational model developed using an Arduino Uno, breadboard, LEDs, push buttons, resistors, and jumper wires. The project demonstrates the major stages of the human digestive system by allowing users to select individual organs and activate their corresponding LED indicators.

The model represents the movement of food through six stages: the mouth, oesophagus, stomach, small intestine, large intestine, and rectum. Each organ is associated with a push button and an LED, making the demonstration simple, visual, and interactive.

The project aims to combine electronics, programming, biology, and engineering concepts to create an affordable STEM-based learning tool.

## 🎯 Objectives

- Demonstrate the major stages of human digestion.
- Develop an interactive, button-controlled educational model.
- Integrate Arduino programming with basic electronic components.
- Improve understanding of digestive organ functions and the path of food.
- Promote practical STEM learning through a working prototype.

## ⚙️ Technologies and Components

- **Microcontroller:** Arduino Uno
- **Programming Language:** Embedded C/C++ (Arduino IDE)
- **Circuit Platform:** Breadboard
- **Output Components:** 6 LEDs
- **Input Components:** 6 push buttons
- **Resistors:** 220 Ω resistors for LED current limiting
- **Connections:** Jumper wires
- **Power Supply:** USB power through the Arduino Uno

## 🔬 Working Principle

Each push button is connected to a digital input pin of the Arduino. When a button is pressed, the Arduino detects the input and activates the corresponding LED to identify the selected digestive organ.

| Digestive Organ | LED Pin | Button Pin |
|---|---|---|
| Mouth | D2 | D8 |
| Oesophagus | D3 | D9 |
| Stomach | D4 | D10 |
| Small Intestine | D5 | D11 |
| Large Intestine | D6 | D12 |
| Rectum | D7 | A0 |

The buttons use the Arduino's internal pull-up configuration (`INPUT_PULLUP`), while the LEDs are connected through 220 Ω resistors to limit current.

## 🧪 Methodology

1. Study the human digestive system and identify the major organs.
2. Design the physical model and determine the placement of each organ.
3. Assemble the Arduino Uno and breadboard circuit.
4. Connect the LEDs and push buttons to their assigned pins.
5. Develop and upload the Arduino program.
6. Test each button and its corresponding LED.
7. Integrate the circuit with the digestive system model.
8. Demonstrate the working prototype.

## 🌟 Key Features

- Interactive organ selection using push buttons.
- Individual LED indicators for six digestive stages.
- Simple and low-cost electronic design.
- Beginner-friendly Arduino implementation.
- Suitable for biology demonstrations and STEM education.
- Expandable design for future features such as an LCD display or additional sensors.

## 🚀 Future Enhancements

- Add a 16×2 LCD to display organ names and explanations.
- Integrate a transparent intestine model to visualize the digestive tract.
- Add animated lighting to demonstrate the sequence of digestion.
- Develop a graphical dashboard for displaying educational information.

## 🎓 Applications

- BTech engineering projects
- School and college science exhibitions
- STEM education and interactive biology lessons
- Educational demonstrations of basic electronics and embedded systems

## 👩‍💻 Project Status

**Development stage:** Working prototype development and testing.

This project demonstrates how Arduino-based electronics can make biological concepts more interactive, understandable, and engaging.

