# 📱 iOS Calculator Clone

A fully functional, pixel-perfect recreation of the iOS calculator. This project serves as a deep dive into **JavaScript state management**, complex conditional logic, and the implementation of high-fidelity UI/UX.

## 🚀 Live Demo
[https://yz-calculator.vercel.app](https://yz-calculator.vercel.app)

## 🛠️ Tech Stack
- **HTML5**: Structured using semantic button elements and a clean display output.
- **CSS3**: Leverages **CSS Grid** for the precise button layout and high-contrast styling.
- **JavaScript (ES6)**: A robust engine that manages the mathematical state machine.

## ✨ Key Features
- **100% Functional Arithmetic**: Supports all standard operations (+, -, ×, ÷) including percentage and sign-toggle functionalities.
- **State Machine Logic**: Engineered to handle complex operational sequences, ensuring that chaining multiple operations follows standard mathematical order.
- **Responsive Interaction**: Interactive button states that mimic the tactile feel of the original iOS interface.
- **Precision Floating Point**: Correctly handles decimal arithmetic and prevents overflow through dynamic display scaling.

## 🧩 Technical Challenge: The Logic Engine
The core challenge of this project was not the UI, but the **internal state management**. I developed a logic engine that tracks the current operand, the operator, and the previous total to ensure the calculator behaves exactly like a physical device:

