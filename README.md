📘 README — Qt C++ Calculator
🧮 Project: Calculator using Qt and C++
This project is a simple calculator application built with the Qt Framework using C++. It has a GUI with basic arithmetic operations, and the scientific version supports additional functions like sine, cosine, and square root.

📂 Project Structure
python
Copy
Edit
Calculator_Qt_CPP.zip/
├── Calculator.pro         # Qt project file
├── main.cpp               # Entry point of the application
├── calculator.h           # Header file for Calculator class
└── calculator.cpp         # Implementation of Calculator class
(For the scientific version: ScientificCalculator_Qt_CPP.zip with extra features like history and functions.)

🔧 Requirements
Qt Creator (recommended)

Qt 5 or Qt 6 SDK

C++ compiler (MinGW or MSVC)

🚀 How to Build
Open Qt Creator

File → Open Project...

Select Calculator.pro (or ScientificCalculator.pro)

Configure a Kit (link with Qt if needed)

Click Build → Run

✅ Features
Basic Version:

Addition, Subtraction, Multiplication, Division

Clear, Equal buttons

Scientific Version:

Decimal support

sin(), cos(), √()

Calculation history

Backspace

Error handling

📦 Output
A GUI calculator window with responsive layout and buttons for interaction.

🙋 Need Help?
If Qt Creator says "No suitable kits found":

Go to Tools → Options → Kits

Under Qt Versions, click Add

Locate your qmake.exe in:

makefile
Copy
Edit
C:\Qt\5.15.2\mingw81_64\bin\qmake.exe
Add a new Kit with a compiler and debugger
