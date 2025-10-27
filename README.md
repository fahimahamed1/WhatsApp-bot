# 🤖 WhatsApp Bot using Baileys

A WhatsApp bot built using **Node.js** and the **@whiskeysockets/baileys** library. It connects to WhatsApp Web using multi-device support, authenticates via QR code, and responds to basic commands like `hi` and `bye`.

---

## ✅ Features
- 🔐 QR-based authentication using WhatsApp Web  
- 💬 Auto-replies:
  - `hi` → Hello from the bot 🤖
  - `bye` → Goodbye 👋
- 🔄 Auto-reconnect on disconnection  
- 💾 Session saved using Multi-File Auth (`auth_info/` folder)

---

## 📦 Installation

### 1. Install Required Packages (Termux or Linux)
```bash
pkg update && pkg upgrade -y
pkg install nodejs git -y
```

### 2. Clone the Repository
```bash
git clone https://github.com/HackersNexus/Whatsapp-Bot
cd Whatsapp-Bot
```

### 3. Install Dependencies
```bash
npm install @whiskeysockets/baileys qrcode-terminal pino
```

---

## 🚀 Run the Bot
```bash
node bot.js
```
- A **QR code** will appear.  
- Scan it from **WhatsApp → Linked Devices**.

---

## 📁 Folder Structure
```
Whatsapp-Bot/
├── auth_info/       # Stores session data
├── bot.js           # Main bot script
└── README.md        # Project documentation
```

---

## 📌 Notes
- Compatible with Termux and Linux  
- Supports only basic text messaging (custom features can be added)  
- Do not delete `auth_info/` unless you want to log out  

---

## 👨‍💻 Author
Made with ❤️ by **Fahim Ahamed**  
Feel free to fork, improve, and contribute!

---

## 📄 License
Licensed under the **MIT License**
