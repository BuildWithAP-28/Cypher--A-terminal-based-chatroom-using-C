# Cypher--A-terminal-based-chatroom-using-C
A lightweight, terminal-based LAN chatroom built in C using Socket Programming (Winsock). It features an interactive client setup for quick connection via IP and port, enabling seamless real-time messaging. Designed for low-latency network communication, it perfectly demonstrates core TCP/IP protocols and multi-client handling in the termina

## ✨ Features
* 🖥️ **Terminal-Based Interface:** Clean, fast, and distraction-free command-line experience.
* 🌐 **LAN Connectivity:** Seamless real-time communication between devices on the same local network.
* ⚡ **Interactive Setup:** Easy-to-use client prompts for Server IP, Port, and Username configuration.
* ⚙️ **Socket Programming:** Implemented using standard C sockets (Windows Socket API) for robust message routing.

## 🛠️ Tech Stack
* **Language:** C
* **Core Concepts:** Socket Programming (Winsock), TCP/IP Protocols, Network I/O.

## 🚀 Getting Started

### Prerequisites
* A C compiler like `gcc` installed on your system (e.g., via MSYS2/MinGW for Windows).
* Windows Operating System (as the project utilizes the `ws2_32` library).

### 🔧 Installation & Compilation
1. Clone the repository to your local machine:
```bash
   git clone [https://github.com/your-username/cypher.git](https://github.com/your-username/cypher.git)
   cd cypher

Compile the server and client files. Note: You must link the Winsock library (-lws2_32) to avoid linker errors.

Bash
   gcc server.c -o server -lws2_32
   gcc client.c -o client -lws2_32

💻 Usage
1. Start the Server in terminal
open the folder in the terminal 
Run the server executable and provide a port number (e.g., 8080) as a command-line argument.

PowerShell
.\server <enter the port numbeer you want>

2. Connect a Client
Run the client executable. It will interactively prompt you for the connection details.

PowerShell
.\client

Enter the server IP address: 192.168.1.30   # Use 127.0.0.1 if testing on the same PC
Enter the server port: 8080
Please enter your name: Ayush


3. Start Chatting!
Once connected successfully, you can start sending messages which will be broadcasted to the chatroom under your chosen name.

🤝 Contributing
Contributions, issues, and feature requests are welcome!

👨‍💻 Author
Ayush Pandey

GitHub: @BuildWithAP-28

