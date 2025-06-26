# 💬 Multi-User Chat Application — Real-Time Socket Chat

A foundational **real-time chat application** demonstrating direct network communication using Python’s `socket` module and concurrent client handling via `threading`. It features a simple server-client architecture that supports **multiple users**, **nickname customization**, and **basic admin commands**.

---

## ✨ Features

- 📡 Instant messaging between multiple clients
- 👥 Server handles concurrent client connections
- 🧑 Clients can use custom nicknames
- 📢 Messages are broadcast to all connected participants
- 🛠️ Admin commands (e.g., `/kick`) for moderation

---

## 💻 Technologies Used

- **Python 3.x**
- `socket` module (for network communication)
- `threading` module (for handling multiple clients)

---

## 🚀 Getting Started

1.	Clone the repository (ensure server.py and client.py are present).
2.	Create and activate a virtual environment (as above).
3.	No external dependencies required.
4.	Open two (or more) separate terminal windows.
5.	In the first terminal, run the server:
6.	python server.py
7.	In the second (and subsequent) terminals, run the client:
8.	python client.py
        -	Enter a nickname when prompted.

