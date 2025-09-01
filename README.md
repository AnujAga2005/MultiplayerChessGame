# ♟️ Chess.com Clone  

A real-time multiplayer chess game built using **Node.js, Express, Socket.IO, and Chess.js**, with a simple front-end powered by **vanilla JS + Tailwind CSS**.  

✅ Two players can play together  
✅ Others can spectate live  
✅ Drag & Drop chess pieces  
✅ Real-time moves synced with Socket.IO  

⚠️ Currently only supports **one game at a time** (working on multi-game support).  
💡 Fun bug: All pawns are purple 👾 – feel free to fix it and submit a PR!  

---

## 🚀 Demo  
(Attach a **screenshot** or a **demo video link** here)

---

## 📦 Tech Stack  
- **Backend:** Node.js, Express, Socket.IO  
- **Game Logic:** [chess.js](https://github.com/jhlywa/chess.js)  
- **Frontend:** HTML, TailwindCSS, Vanilla JS  
- **View Engine:** EJS  

---

## 🛠️ Installation & Setup  

1. Clone the repo  
   ```bash
   git clone https://github.com/AnujAga2005/MultiplayerChessGame.git
   cd MultiplayerChessGame


2. Install dependencies
   ```bash
   npm install

3. Run the server
   ```bash
   npx nodemon
  
Server will start at http://localhost:3000

---

## 🎮 How It Works

First player to join becomes White

Second player becomes Black

Additional users become Spectators

Moves are validated using chess.js and synced to all clients via Socket.IO

Board auto-flips for Black

---

## 📸 Features Preview

✅ Real-time multiplayer chess

✅ Spectator mode

✅ Drag & Drop interface

✅ Board flip for Black

🚧 Coming soon: Multiple games support

---

## 🐛 Known Issues

All pawns appear as purple pieces (PRs welcome!)

Only one game can run at a time

---

## 🤝 Contributing

Fork the project

Create your feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add some feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

---

## 📜 License

This project is open-source under the MIT License
.
