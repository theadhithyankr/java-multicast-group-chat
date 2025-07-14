
# 💬 GroupChat-Multicast – Java Group Chat via Multicast Sockets

A lightweight Java-based group chat application that uses **multicast communication** to enable real-time chatting across multiple users on the same network.

Built to demonstrate Java's networking capabilities using UDP multicast sockets.

---

## 🛠 Features

- 📡 Multicast-based message broadcasting  
- 💻 Terminal-based client interface  
- 🔁 Continuous message listening via threads  
- 🚫 No external libraries required — Pure Java  
- 🧪 Great for learning socket programming

---

## 🚀 How to Run

### 1. Compile the Java files:

```bash
javac GroupChat.java ReadThread.java
````

> Ensure your terminal is inside the `src/` directory (if applicable).

### 2. Run the chat client:

```bash
java GroupChat <multicast-address> <port-number>
```

**Example:**

```bash
java GroupChat 230.0.0.0 4446
```

Now open **multiple terminals** and run the above command in each to simulate multi-user chatting.

---

## 🧠 How It Works

* `GroupChat.java`: Main client that sends messages and starts a listener thread
* `ReadThread.java`: Listens for incoming messages using a multicast socket
* Users joining the same multicast group can see each other’s messages

---

## 📦 File Structure

```
GroupChat-Java-Multicast-Chat-App/
├── src/
│   ├── GroupChat.java
│   └── ReadThread.java
├── .gitignore
└── README.md
```

---

## 🔐 Requirements

* Java JDK 8 or later
* Works on any OS with terminal and local network

---

## 📄 License

MIT License — use, modify, and share freely.

---

## 🧑‍💻 Author

Built with 🔥 by [@theadithyankr](https://github.com/theadhithyankr)
Networking fundamentals made simple.


