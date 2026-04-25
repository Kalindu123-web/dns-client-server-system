# 🌐 DNS & Client-Server System 🚀

![Linux](https://img.shields.io/badge/OS-Linux-blue?logo=linux)
![C](https://img.shields.io/badge/Language-C-orange?logo=c)
![BIND](https://img.shields.io/badge/DNS-BIND-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📌 Overview

A real-world networking project that demonstrates:

✨ Authoritative DNS Server (BIND)
✨ Forward & Reverse DNS resolution
✨ TCP Client-Server communication using C
✨ Session logging system
✨ Mail server DNS (MX records)

---

## 🧠 Architecture

```
Client (23.74.33.20)
        │
        │  TCP Connection (Port 8080)
        ▼
Server (23.74.33.10)
        │
        │  DNS Queries (Port 53)
        ▼
DNS Server (BIND)
```

---

## 🌐 DNS Configuration

### 🔹 Forward DNS

```
IT23743380.lk        → 23.74.33.10
kalindu3380          → 23.74.33.10
kalindu3380cli       → 23.74.33.20
```

### 🔹 Reverse DNS

```
23.74.33.10 → achindu4940.IT23534940.lk
23.74.33.20 → achindu4940cli.IT23534940.lk
```

---

## 💻 Client-Server System

### 🔹 Features

✔ TCP socket communication
✔ Iterative server design
✔ Sends real-time server date & time
✔ Logs client connections
✔ Handles multiple client sessions

---

## ⚙️ Technologies Used

| Category   | Technology     |
| ---------- | -------------- |
| OS         | Linux (CentOS) |
| DNS        | BIND (named)   |
| Language   | C              |
| Networking | TCP/IP         |

---

## 🚀 How to Run

### 🔧 Compile

```bash
gcc server.c -o server
gcc client.c -o client
```

### ▶️ Run Server

```bash
./server
```

### ▶️ Run Client

```bash
./client
```

---

## 🧪 DNS Testing

```bash
dig @23.74.33.10 IT23743380.lk
dig kalindu3380.IT23743380.lk
dig -x 23.74.33.10
```

## 🎯 Learning Outcomes

✔ DNS Zone Configuration
✔ Socket Programming
✔ Network Troubleshooting
✔ Linux Server Management

---

## 👨‍💻 Author

**Kalindu Methmuditha**
🎓 Software Engineering Student


---

⭐ If you like this project, give it a star!
