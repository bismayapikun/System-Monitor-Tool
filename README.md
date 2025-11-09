# 🖥️ System Monitor Tool (Capstone Project)

A console-based **System Monitor Tool** written in **C++** that displays real-time system information like **CPU usage**, **memory consumption**, and **active processes**.  
The project was developed for **Assignment 3 (LSP)** as part of the **Capstone Project series**.

---

## 🚀 Features

- Displays live process information (**PID**, **Name**, **CPU%**, **MEM%**)
- Sorts by **CPU** or **Memory** usage (`s` to toggle)
- Allows killing processes by **PID** (`k <pid>`)
- Updates automatically every **2 seconds**
- Runs directly in the **terminal** (no GUI dependencies)

---

## ⚙️ Technologies Used

- **Language:** C++ (C++17)  
- **Libraries:** `<thread>`, `<chrono>`, `<dirent.h>`, `<fstream>`, `<iomanip>`  
- **Platform:** Linux (WSL on Windows)

---

## 🧩 How to Run

### 1. Install dependencies
```bash
sudo apt update && sudo apt install build-essential -y
```

## 2. Clone this repository

```
git clone https://github.com/bismayapikun/system-monitor-tool.git
cd system-monitor-tool
```
## 3. Build the project
```
make
```
## 4. Run the tool
```
./sysmon
```
## 🎮 Controls
Command                     Action

s                    Toggle sort between CPU% and MEM%

k                    Kill process by PID

q                    Quit the program

## 📂 Project Structure
```
system-monitor-tool/
├── src/
│   └── main.cpp
├── Makefile
└── README.md
```

## 🧾 Author
- Name: Bismaya Ranjan Sahoo

- Platform: Windows (WSL Ubuntu)

- Language: C++


## 🏆 Conclusion
This project implements process management, CPU/memory tracking, and interactive system control using Linux system programming in C++.

It meets all requirements of Assignment 3 (LSP) and demonstrates real-time system monitoring capabilities effectively.

## 💾 Save Instructions (for terminal editors)

- Press Ctrl + O, then Enter to save

- Press Ctrl + X to exit
