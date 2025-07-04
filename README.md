
# 💻 Real-Time Network Intrusion Detection Web App

A real-time intrusion detection system built with **Flask** and **Machine Learning**, capable of identifying both known and unknown threats by analyzing live network traffic.

---

## 🚀 Features

* 📡 Real-time network packet sniffing using `Scapy`.
* 🔐 Detection of **known attacks** with a **Random Forest (RF)** classifier trained on **CICIDS 2018** and **SCVIC-APT** datasets.
* 🧠 Detection of **unknown anomalies** using an **Autoencoder (AE)** model.
* 📊 Interactive web-based dashboard built with **Flask**, **SocketIO**, and **Plotly**.
* 🌍 Country-based IP flag visualizations using `ipinfo.io`.

---

## 🧠 System Architecture

![System Diagram](https://github.com/HoangNV2001/Real-time-IDS/assets/72451372/78e0b74c-9db6-4bf5-8591-6d7aa8247b22)

---

## 🛠 Requirements

### Operating System

* **Windows OS** (recommended)

### Dependencies

1. **Python 3.9**

   * [Download (64-bit)](https://www.python.org/ftp/python/3.9.13/python-3.9.13-amd64.exe)
   * [Download (32-bit)](https://www.python.org/ftp/python/3.9.13/python-3.9.13.exe)

   > ✅ **Important**: Ensure you check the box: **"Add Python 3.9 to PATH"** during installation.

2. **Npcap 1.71**

   * [Download Npcap](https://npcap.com/dist/npcap-1.71.exe)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/RAGULRAAJAN/Network-Intrusion-Detection-WebApp.git
cd Network-Intrusion-Detection-WebApp/APT_Detection
```

### 2. Create and Activate a Virtual Environment

```bash
python3.9 -m venv venv
# Activate (Windows)
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Flask web server:

```bash
python application.py
```

Visit the web interface at: [http://localhost:5000](http://localhost:5000)

---

## 🖥️ Web Interface Preview

### 📌 Real-Time Flow Monitoring

![Main Page](https://github.com/user-attachments/assets/a99af514-7534-4b1a-be55-31f026223d1c)

---

### 🔍 Flow Details and Explanation

![Flow Detail](https://github.com/user-attachments/assets/dc0a6e5a-c8ea-4c4c-9642-2ace01dde766)

---

## 👨‍💻 Author

**RAGUL RAAJAN THIRUPATHI**
Hacker | Security Analyst
[GitHub](https://github.com/RAGULRAAJAN)

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.


