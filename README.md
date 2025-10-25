🧮 Qt C++ Calculator

A clean and efficient GUI calculator built using the Qt Framework in C++, supporting both basic and scientific operations.

📘 Overview

This project demonstrates how to design and implement a calculator with Qt Widgets.
It includes two versions:

Basic Calculator — Performs standard arithmetic.

Scientific Calculator — Adds trigonometric and advanced mathematical functions.

📂 Project Structure
Calculator_Qt_CPP/
├── Calculator.pro         # Qt project file
├── main.cpp               # Entry point of the application
├── calculator.h           # Header for Calculator class
└── calculator.cpp         # Implementation of Calculator logic


Scientific Version:
ScientificCalculator_Qt_CPP/ — Includes extra modules like history, sin, cos, and √ functions.

🔧 Requirements

Qt Creator (recommended IDE)

Qt 5.x or Qt 6.x SDK

C++ compiler: MinGW or MSVC

🚀 How to Build & Run

Open Qt Creator

Click File → Open Project...

Select Calculator.pro (or ScientificCalculator.pro)

Configure a Kit (connect to Qt SDK if needed)

Click Build → Run

✅ Features
🧾 Basic Version

➕ Addition

➖ Subtraction

✖️ Multiplication

➗ Division

🧹 Clear, Equal buttons

🧠 Scientific Version

🔢 Decimal support

📈 sin(), cos(), √()

🕒 Calculation history

⌫ Backspace functionality

⚠️ Error handling

📦 Output

A modern GUI calculator with responsive layout and intuitive buttons.
Supports both keyboard and mouse input for smooth operation.

🛠 Troubleshooting

If you see "No suitable kits found" in Qt Creator:

Go to Tools → Options → Kits

Under Qt Versions, click Add

Locate your qmake.exe file, for example:

C:\Qt\5.15.2\mingw81_64\bin\qmake.exe


Add a new Kit with the correct compiler and debugger.

🏷️ Tags

#cpp #qt #gui #calculator #desktopapp #qtcreator

🧑‍💻 Author

Deepjyoti Das
🔗 https://www.linkedin.com/in/deepjyotidas1

💻 GitHub
