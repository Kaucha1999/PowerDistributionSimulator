# ⚡ Power Distribution & Load Management Simulator

A C++ simulation project that models power distribution from transformers to consumer loads via busbars. The system simulates real-world load shedding, transformer limits, and power priority, suitable for educational and engineering applications.

## 👨‍🔧 About the Project

This simulator was created by Electrical and Electronics Engineering students with real-world hydropower experience. It aims to:
- Simulate power supply behavior in a mini-grid or substation
- Distribute limited transformer capacity among various loads
- Implement load shedding based on priority
- Provide a modular architecture with transformers, busbars, and loads

## 🧱 System Architecture

- `ControlCenter`: Manages the simulation
- `Grid`: Contains transformers in a region
- `Transformer`: Supplies power with capacity limits
- `Busbar`: Connects loads to transformers
- `Load`: Represents power consumers (house, factory, hospital)

## 🚀 Features

- Priority-based load distribution (e.g., hospital gets power first)
- Transformer capacity limits and utilization reports
- Easy-to-extend modular C++ design
- Console-based simulation loop
- Power status reports (supplied / shed)

## 🛠️ Tech Stack

- Language: C++17
- CLI-based interface (optional GUI later)
- No external dependencies

## 📦 Getting Started

```bash
git clone https://github.com/Kaucha1999/power-distribution-simulator.git
cd powerdistributionsimulator
g++ main.cpp -o simulator
./simulator
