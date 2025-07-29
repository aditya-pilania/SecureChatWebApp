# 🔒 Secure Chat – End-to-End Encrypted Messaging Application

[![Live App](https://img.shields.io/badge/Live%20Demo-SecureChat-blue?style=for-the-badge&logo=render)](https://securechat-3awc.onrender.com/)

Secure Chat is a secure real-time messaging web application that demonstrates **End-to-End Encryption (E2EE)** using a hybrid of RSA and AES. The platform is designed for educational purposes, showcasing how encrypted chat systems function at both the client and server levels.

---

## 📌 Features

- 🔐 **User registration & login** with secure password hashing
- 🔑 **RSA public-private key pair generation** per user
- 🧠 **AES encryption** for message confidentiality
- 📡 **WebSocket-based real-time messaging** (via Socket.IO)
- 🧾 **Room-based communication**
- 🌐 **Mobile-friendly interface**
- 🚀 **Publicly accessible deployment on Render**

---

## 🔧 Tech Stack

| Layer             | Technologies Used                        |
|------------------|-------------------------------------------|
| Backend           | Python Flask                             |
| Real-time Comm.   | Flask-SocketIO + Eventlet                |
| Encryption        | RSA (2048-bit), AES (CBC)                |
| Crypto Library    | Python `cryptography` module             |
| Frontend          | HTML, CSS, JavaScript                    |
| Authentication    | Flask-Login, Werkzeug                    |
| Database          | SQLAlchemy (SQLite for local / PostgreSQL for Render) |
| Hosting           | Render.com                               |

---

## 🚧 Current Limitation

> 🔸 Although **Diffie-Hellman (DH)** and **HKDF**-based dynamic session key derivation were partially implemented, the current version uses a **static AES key encrypted with RSA** for message transmission. The full E2EE implementation using ephemeral DH remains on hold due to downstream integration issues.

---

## 🌐 Live Demo

**🔗 Try it here → [https://securechat-3awc.onrender.com/](https://securechat-3awc.onrender.com/)**

✅ No installation required — simply sign up and start chatting securely.

---

## 📄 License

This project is developed and shared for **educational and demonstration purposes only**. Do not use it in production environments without further security audits.

---

## ✍️ Author

**Aditya Pilania**  
Built with 💻, ⚙️, and ☕ for learning and sharing secure communication principles.

