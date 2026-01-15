<div align="center">

# 🍅 Pomodoro Timer

**A productivity-focused desktop application implementing the Pomodoro Technique**

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green.svg)](https://docs.python.org/3/library/tkinter.html)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

[Features](#-features) •
[Installation](#-installation) •
[Usage](#-usage) •
[Screenshots](#-screenshots) •
[Contributing](#-contributing)

</div>

---

## 📖 About

The **Pomodoro Timer** is a clean, intuitive desktop application built with Python and Tkinter that helps you maximize productivity using the proven Pomodoro Technique. Break your work into focused intervals separated by short breaks to maintain peak mental performance throughout your day.

### What is the Pomodoro Technique? 

The Pomodoro Technique is a time-management method developed by Francesco Cirillo that uses a timer to break work into intervals, traditionally: 

1. **Work** for 25 minutes (Pomodoro)
2. Take a **5-minute break**
3. After 4 Pomodoros, take a **15-30 minute break**

This application uses customized intervals optimized for deep work sessions: 
- 🎯 **45 minutes** of focused work
- ☕ **15 minutes** short breaks
- 🌙 **20 minutes** long break (after 4 work sessions)

---

## ✨ Features

- ⏱️ **Customizable Timer Cycles** – 45-minute work sessions with automatic break intervals
- 🔄 **Automatic Cycle Management** – Seamlessly switches between work and break periods
- ✅ **Progress Tracking** – Visual checkmarks display completed work sessions
- 🎨 **Clean User Interface** – Minimalist design with a tomato-themed aesthetic
- 🔔 **Session Indicators** – Color-coded labels (Work/Break) for instant status recognition
- 🔁 **Reset Functionality** – Restart your timer at any point
- 💻 **Lightweight** – Minimal resource usage, runs smoothly on any system

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Python 3.x** | Core programming language |
| **Tkinter** | GUI framework |
| **Math module** | Time calculation utilities |

---

## 📦 Installation

### Prerequisites

- Python 3.x installed on your system
- Tkinter (usually comes pre-installed with Python)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Garvv-Mittal/pomodoro-timer.git
   cd pomodoro-timer
   ```

2. **Verify Python installation**
   ```bash
   python --version
   ```

3. **Run the application**
   ```bash
   python main.py
   ```

---

## 🚀 Usage

1. **Start the Timer**:  Click the "Start" button to begin your first work session
2. **Work Session**: Focus on your task for the 45-minute work period
3. **Break Time**:  Automatically switches to a 15-minute break
4. **Track Progress**: Check marks (✅) appear after each completed work session
5. **Long Break**: After 4 work sessions, enjoy a 20-minute long break
6. **Reset**: Click "Reset" to restart the cycle at any time

### Customizing Timer Intervals

Edit the constants in `main.py` to adjust session lengths: 

```python
WORK_MIN = 45          # Work session duration
SHORT_BREAK_MIN = 15   # Short break duration
LONG_BREAK_MIN = 20    # Long break duration (after 4 sessions)
```

---

## 📁 Project Structure

```
pomodoro-timer/
├── main.py           # Main application logic and GUI
├── tomato.png        # Tomato icon graphic
└── Readme.md         # Project documentation
```

---

## 🎨 Screenshots

<!-- Add screenshots here when available -->
_Coming soon:  Application screenshots showing the timer in action_

---

## 🔮 Future Enhancements

- [ ] Sound notifications when sessions end
- [ ] Customizable timer presets
- [ ] Session statistics and analytics
- [ ] Dark mode theme
- [ ] Configurable work/break durations via GUI
- [ ] Task list integration
- [ ] Session history tracking

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Garvv Mittal**

- GitHub: [@Garvv-Mittal](https://github.com/Garvv-Mittal)

---

## 🙏 Acknowledgments

- Inspired by the Pomodoro Technique® by Francesco Cirillo
- Built with Python's Tkinter library
- Tomato icon design for visual appeal

---

<div align="center">

**⭐ Star this repository if you find it helpful! **

Made with ❤️ and ☕

</div>
