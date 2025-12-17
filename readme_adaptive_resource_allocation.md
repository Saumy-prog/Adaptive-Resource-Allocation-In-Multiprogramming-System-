# Adaptive Resource Allocation in Multiprogramming Systems (C++)

## 📌 Overview
This project is a **C++ simulation of adaptive resource allocation in a multiprogramming operating system**. It demonstrates how multiple processes compete for limited system resources and how the operating system allocates those resources safely and fairly. The project is mainly intended for **educational and academic use**, especially for understanding core **Operating System concepts**.

Each process behaves like a real OS process with its own maximum resource need, current allocation, priority, waiting time, and execution cycles. The simulation runs step-by-step and shows how the system avoids unsafe states while keeping the workload balanced.

---

## ⚙️ Key Features
- Simulation of **multiprogramming environment**
- **Adaptive resource allocation** based on process behavior
- **Banker’s Algorithm–style safe state check**
- Priority-based scheduling with **starvation prevention (aging)**
- Dynamic process resource requests
- Clear **ASCII-based console visualization**
- Detailed **simulation summary report**
- Resource allocation logging to file

---

## 🧠 Concepts Demonstrated
- Resource Allocation
- Deadlock Avoidance
- Safe and Unsafe States
- Starvation Prevention
- Priority Scheduling
- Multiprogramming Systems
- Process Management

---

## 🛠️ Technologies Used
- **Language:** C++
- **Libraries:** `<iostream>`, `<vector>`, `<iomanip>`, `<fstream>`, `<windows.h>`
- **Platform:** Windows (uses `Sleep()`)

---

## ▶️ How to Run

### Compile
```bash
g++ resource_simulation.cpp -o resource_simulation
```

### Execute
```bash
resource_simulation
```

---

## 📄 Output
- Cycle-by-cycle console display of process status
- Allocation, need, priority, and waiting time for each process
- Visual bar representation using ASCII characters
- Final summary showing total cycles and process completion status
- Log files generated:
  - `simulation_log.txt`
  - `resource_log.txt`

---

## 🎓 Use Cases
- Operating Systems Laboratory
- Academic Mini / Major Projects
- Viva and Exam Preparation
- Learning Deadlock Avoidance and Resource Management

---

## 📌 Note
This project is a **simulation**, not a real operating system implementation. It is built to help learners visualize how adaptive resource allocation and deadlock avoidance work in multiprogramming systems.

---

## 👤 Author
Developed for educational purposes. You are free to modify, extend, and experiment with the code for learning and academic use.
