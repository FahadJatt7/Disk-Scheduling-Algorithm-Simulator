<div align="center">

# 💽 Disk Scheduling Simulator

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Tkinter-GUI-orange?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge&logo=plotly&logoColor=white" />

<br/>

> 🖴 An interactive **Disk Scheduling Algorithm Simulator** with real-time visualization — compare FCFS, SSTF, SCAN, C-SCAN, LOOK, and C-LOOK side by side!

<br/>

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=flat-square&logo=python)](https://python.org)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()
[![OS Concepts](https://img.shields.io/badge/Topic-Operating%20Systems-blueviolet?style=flat-square)]()

</div>

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Algorithms Implemented](#-algorithms-implemented)
- [How to Run](#-how-to-run)
- [Usage Guide](#-usage-guide)
- [Project Structure](#-project-structure)
- [Developers](#-developers)

---

## 🚀 Project Overview

This project is a **GUI-based Disk Scheduling Simulator** built using Python's Tkinter library. It allows users to input disk requests and an initial head position, then simulate and compare multiple OS disk scheduling algorithms — complete with **seek time calculations** and **graphical movement charts**.

Designed as an educational tool for Operating Systems coursework, it brings abstract algorithms to life through an intuitive dark-themed interface.

---

## ✨ Features

- 🎯 **6 Scheduling Algorithms** — All major disk scheduling strategies in one place
- ⚖️ **Side-by-Side Comparison** — Run all algorithms at once and compare seek times
- 📊 **Live Graph Visualization** — Matplotlib chart showing disk head movement
- 📋 **Results Table** — Clean tabular output for all algorithm results
- 🌑 **Dark Theme UI** — Sleek, modern dark interface built with Tkinter
- ⚡ **Instant Output** — Sequence and seek time displayed immediately

---

## 🧮 Algorithms Implemented

| Algorithm | Type | Description |
|-----------|------|-------------|
| **FCFS** | Non-Preemptive | Services requests in the order they arrive |
| **SSTF** | Non-Preemptive | Always picks the closest request to the current head |
| **SCAN** | Preemptive | Moves in one direction, services requests, reverses at end |
| **C-SCAN** | Preemptive | Like SCAN, but jumps back to start (circular, no reverse servicing) |
| **LOOK** | Preemptive | Like SCAN, but only goes as far as the last request |
| **C-LOOK** | Preemptive | Like C-SCAN, but jumps to the first request (not disk end) |

---

## 🖥️ How to Run

### Option 1 — Run the Executable (Easiest)

```
1. Download DiskScheduler.exe
2. Double-click to launch — no installation needed!
```

### Option 2 — Run from Python Source

**Prerequisites:**
```bash
pip install matplotlib
```

**Run:**
```bash
python DiskScheduler.py
```

---

## 📖 Usage Guide

```
1. Enter disk requests (space-separated) in the first input field
   Example:  98 183 37 122 14 124 65 67

2. Enter the initial head position
   Example:  53

3. Click any single algorithm button (FCFS, SSTF, etc.) to run individually
   — OR —
   Click "Run All + Compare" to see all algorithms at once

4. View results in the output label, comparison table, and pop-up graph!
```

---

## 📁 Project Structure

```
DiskScheduler/
│
├── DiskScheduler.py       # Main application source code
├── DiskScheduler.exe      # Standalone executable (Windows)
└── README.md              # Project documentation
```

---

## 👨‍💻 Developers

<div align="center">

| | Developer |
|---|-----------|
| 💻 | **Fahad Maqsood** |
| 💻 | **Abdul Moiz** |
| 💻 | **Bilal Lateef** |

🎓 **BS Information Technology — 5th Semester (2023–27)**

🏫 **University of Kotli, AJK**

</div>

---

## 📚 Conclusion

This simulator bridges theory and practice — making disk scheduling algorithms intuitive and easy to understand. Whether you're a student exploring OS concepts or a developer curious about I/O optimization, this tool gives clear visual insight into how an OS handles disk access efficiently.

---

<div align="center">

*Built with 💙 for Operating Systems coursework*

⭐ **Star this repo if it helped you!** ⭐

</div>
