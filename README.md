# FCFS CPU Scheduling Algorithm Simulator

A web-based interactive simulator for the **First Come First Serve (FCFS)** CPU scheduling algorithm. Built with vanilla HTML, CSS, and JavaScript — no dependencies, runs entirely in the browser.

## 🖥️ Demo

Open `index.html` in any modern browser to run the simulator locally.

## 📌 About FCFS

**First Come First Serve (FCFS)** is the simplest CPU scheduling algorithm. Processes are executed in the exact order they arrive in the ready queue — the first process to arrive gets the CPU first.

- **Type:** Non-preemptive
- **Queue:** FIFO (First In, First Out)
- **Suitable for:** Batch systems where order of execution matters

## ✨ Features

- Input multiple processes with **Arrival Time** and **Burst Time**
- Automatically computes:
  - **Completion Time**
  - **Turnaround Time** (Completion Time − Arrival Time)
  - **Waiting Time** (Turnaround Time − Burst Time)
  - **Average Waiting Time**
  - **Average Turnaround Time**
- Visual **Gantt Chart** showing process execution order
- Clean, responsive UI

## 🚀 Getting Started

No installation or setup required.

```bash
# Clone the repository
git clone https://github.com/Yashhh0602/FCFS-Scheduling-Algorithm.git

# Navigate into the project folder
cd FCFS-Scheduling-Algorithm/CPUScheduler-main

# Open in browser
open index.html
```

Or simply double-click `index.html` to open it in your browser.

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML | Structure & layout |
| CSS | Styling & responsiveness |
| JavaScript | Algorithm logic & DOM manipulation |

## 📊 How It Works

1. Enter the number of processes
2. Input **Arrival Time** and **Burst Time** for each process
3. Click **Calculate / Simulate**
4. View the **Gantt Chart** and the computed metrics table

### Example

| Process | Arrival Time | Burst Time | Completion Time | Turnaround Time | Waiting Time |
|---------|-------------|------------|----------------|----------------|--------------|
| P1 | 0 | 4 | 4 | 4 | 0 |
| P2 | 1 | 3 | 7 | 6 | 3 |
| P3 | 2 | 5 | 12 | 10 | 5 |

- **Average Turnaround Time:** (4 + 6 + 10) / 3 = **6.67 ms**
- **Average Waiting Time:** (0 + 3 + 5) / 3 = **2.67 ms**

## ⚠️ Limitations of FCFS

- Can cause the **Convoy Effect** — short processes get stuck waiting behind long ones
- Not ideal for time-sharing or interactive systems
- Does not consider burst time, so average waiting time can be high

## 📁 Project Structure

```
FCFS-Scheduling-Algorithm/
└── CPUScheduler-main/
    ├── index.html      # Main entry point
    ├── style.css       # Styling
    └── script.js       # FCFS algorithm logic
```

## 👤 Author

**Yashvardhan Khanduja**
- GitHub: [@Yashhh0602](https://github.com/Yashhh0602)
- LinkedIn: [yashvardhan-khanduja07](https://linkedin.com/in/yashvardhan-khanduja07)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
