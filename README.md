<div align="center">
	<h1>🦀🚀 Blockchain Infrastructure</h1>
	<p><img src="https://img.shields.io/badge/Rust-Blockchain-orange?logo=rust&logoColor=white" alt="Rust Blockchain Badge"/></p>
	<p><b>Simple, educational blockchain implementation in Rust</b></p>
	<p>🔗💡 <i>Learn the basics of blockchain and P2P networking!</i></p>
</div>

---

## ✨ Features

- ⚡️ Peer-to-peer networking
- ⛓️ Simple blockchain logic
- 🏗️ Block creation (mining)
- 📡 Block broadcasting
- 🦀 Written in Rust

---

## 🚀 Getting Started

```bash
RUST_LOG=info cargo run
```

This starts a local blockchain client. <br>
<b>Note:</b> The blockchain is <b>not persisted</b> (in-memory only).

You can open <b>multiple terminals</b> to run several connected P2P clients.

---

## 💻 Commands

| Command                     | Description                                               |
| --------------------------- | --------------------------------------------------------- |
| <code>ls p</code>           | 👥 List connected peers                                   |
| <code>ls c</code>           | 📜 Print the local blockchain                             |
| <code>create b $data</code> | ⛏️ Mine a new block with <code>$data</code> and broadcast |

---

## 🔄 How It Works

- When a block is created, it is broadcast to all peers. 📨
- Each node updates its blockchain if the new block is valid. 🔄
- On startup, a node requests the blockchain from peers and adopts the longest valid chain. 🏆

---

## ⚠️ Disclaimer

> **This project is for educational purposes only!**
>
> - 🧪 Overly simplified, offline, inefficient, and insecure
> - ❌ Not suitable for production
> - 🛠️ Great for learning and experimenting

Have fun and happy hacking! 😄🦀
