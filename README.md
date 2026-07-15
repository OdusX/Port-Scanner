# Multi-Threaded Port Scanner

## 🛡️ Overview
A high-performance, multi-threaded port scanner written in Python. Designed for rapid network reconnaissance, this tool allows security analysts to quickly map open ports, identify running services, and evaluate network attack surfaces.

## 🚀 Features
- **Multi-Threaded Execution**: Leverages Python's `threading` module to scan multiple ports concurrently, significantly reducing scan times.
- **Dynamic CLI Arguments**: Custom target IP/domain, port ranges, and thread counts passed directly via command-line arguments.
- **Robust Exception Handling**: Gracefully handles host resolution failures, connection timeouts, and user interrupts (`Ctrl+C`).
- **Containerized Deployment**: Includes a production-ready `Dockerfile` for easy execution across isolated environments.

## 📦 Installation & Setup

### Prerequisites
- Python 3.x
- Docker (Optional, for containerized run)

### Cloning the Repository
```bash
git clone [https://github.com/OdusX/Port-Scanner.git](https://github.com/OdusX/Port-Scanner.git)
cd Port-Scanner
