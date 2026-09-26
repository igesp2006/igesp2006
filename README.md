<div align="center">

# Hey, I'm Garvit 👋

### B.Tech CSE Student · Builder · Learning by Building

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=600&lines=Python+%7C+C+%7C+C%2B%2B;Software+%2B+Hardware;Building+things%2C+breaking+things%2C+learning+from+both." alt="Typing SVG">

</div>

---

## About Me

I'm a **B.Tech CSE student** interested in the space between software and hardware.

I like taking an idea, turning it into something that actually works, and then gradually cleaning up the messy first version into a proper project.

- 🐍 Mainly working with **Python**
- ⚙️ Learning **C, C++ and better software architecture**
- 🔧 Interested in **embedded systems and hardware**
- 🖥️ Building desktop tools and hardware-connected projects
- 🌱 Currently focused on writing cleaner, more maintainable code
- 🛠️ Learning by building instead of just collecting tutorials

---

## Tech Stack

### Languages

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,c,cpp&theme=dark" alt="Python C C++">
</p>

### Tools & Development

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,linux&theme=dark" alt="Git GitHub VS Code Linux">
</p>

### Frameworks & Libraries

<p align="left">

  <img src="https://skillicons.dev/icons?i=flask&theme=dark" alt="Flask">

  <br><br>

  <img src="https://img.shields.io/badge/CustomTkinter-1B1825?style=flat-square&logo=python&logoColor=white" alt="CustomTkinter">
  <img src="https://img.shields.io/badge/Tkinter-1B1825?style=flat-square&logo=python&logoColor=white" alt="Tkinter">
  <img src="https://img.shields.io/badge/NumPy-1B1825?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/PyInstaller-1B1825?style=flat-square&logo=python&logoColor=white" alt="PyInstaller">

</p>

### Embedded & Hardware

<p align="left">
  <img src="https://skillicons.dev/icons?i=arduino,platformio,esp32&theme=dark" alt="Arduino PlatformIO ESP32">
</p>

---

# Projects

## 🎮 ETS2 Force Feedback

A Python-based Force Feedback system built around **Euro Truck Simulator 2 telemetry**.

The project connects game telemetry with physical controller feedback to make driving events more noticeable through the wheel/controller.

### Features

- FunBit telemetry integration
- XInput rumble feedback
- Redline feedback
- Cold-start feedback
- Configurable project structure
- Windows release built with PyInstaller
- Separate configuration and asset handling

### Built With

`Python` `FunBit` `XInput` `Tkinter` `CustomTkinter` `PyInstaller`

---

## 🖥️ FunBeat

A hardware + software project built around a physical desktop control interface.

The system combines an **ESP32, TFT display, physical controls and a Python controller** for media, system controls and other desktop interactions.

The idea is simple:

> Make the desk itself feel more interactive instead of having everything live behind a screen.

### Architecture

```text
        Physical Controls
               │
               ▼
        ┌──────────────┐
        │    ESP32     │
        │ TFT + Input  │
        └──────┬───────┘
               │
        Serial / Communication
               │
               ▼
        ┌──────────────┐
        │    Python    │
        │   Controller │
        └──────┬───────┘
               │
       ┌───────┼────────┐
       ▼       ▼        ▼
     Media   Server     UI
