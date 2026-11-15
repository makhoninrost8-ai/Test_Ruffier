# Heart Rate & Ruffier Test App

A cross-platform desktop and mobile application built with **Python** and **Kivy** to perform the Ruffier test and evaluate cardiovascular performance under physical exertion. 

Developed as part of practical software engineering studies and algorithmic problem-solving practice.


## 🚀 Features

- **Multi-Screen Workflow:** Guided step-by-step health assessment using Kivy's `ScreenManager`.
- **Interactive Timers:** Custom real-time countdown/chronometer component (`Seconds`) built with asynchronous clock scheduling (`kivy.clock`).
- **Automated Health Indexing:** Implements the mathematical formula for the Ruffier index, factoring in user age and three pulse measurements (at rest, immediately after squats, and after recovery).
- **Clean Architecture:** Modular code structure separating UI screens, test instructions, calculation logic, and timer components.


## 📁 Project Structure

```text
Test_Ruffier
│
├── main.py          # Application entry point and screen management
├── instructions.py  # Localized UI text and test instructions
├── ruffier.py       # Ruffier test mathematical logic and evaluation thresholds
├── seconds.py       # Reusable Kivy timer component
├── requirements.txt # Project dependencies
└── README.md        # Project documentation

## Installation &  Run

1. **Install dependencies:**
        bash
    pip install -r requirements.txt

2. **Run the application:**
        bash
    python main.py