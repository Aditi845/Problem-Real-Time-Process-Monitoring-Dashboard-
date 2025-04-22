# 🔍 Real-Time System Monitoring Dashboard

A real-time system resource and process monitoring dashboard built with **Flask**, **Socket.IO**, and **psutil**. It displays live system stats including **CPU**, **memory**, **disk usage**, and **currently running processes**.

---

## ⚙️ Features

- 📡 Real-time updates using WebSockets (every 2 seconds)
- 📊 Displays CPU, RAM, and Disk usage in percentage
- 🧠 Lists all running processes with:
  - PID
  - Process Name
  - CPU Usage %
  - Memory Usage %
- 💻 Clean, modern dark UI
- 🔁 Auto-refreshes without reloading the page

---

## 📦 Tech Stack

| Layer       | Technology        |
|-------------|-------------------|
| Backend     | Flask, Flask-SocketIO, Eventlet, psutil |
| Frontend    | HTML5, JavaScript, CSS |
| Realtime    | WebSockets (via Flask-SocketIO) |

---

## 🛠️ Installation & Setup Guide

### 📌 Prerequisites
- Python 3.7 or higher
- Git (optional)

---

### ✅ Step 1: Clone the Repository

--bash
git clone https://github.com/yourusername/real-time-monitoring-dashboard.git
cd real-time-monitoring-dashboard



 Create a Virtual Environment (Optional but Recommended)
On Windows:

python -m venv venv
venv\Scripts\activate

On macOS/Linux:

python3 -m venv venv
source venv/bin/activate

If you face PowerShell script execution error on Windows, run:

Set-ExecutionPolicy RemoteSigned

    🔐 Run this as Administrator, then confirm with Y.

✅ Step 3: Install Required Python Libraries

pip install flask flask-socketio eventlet psutil

✅ Step 4: Run the Flask App

python app.py

    The server will start at http://localhost:5000.

✅ Step 5: Open in Browser

Open your web browser and navigate to:

http://localhost:5000

You'll see a real-time dashboard showing your system resource usage and running processes.
