# TracSignal — P2P Crypto Intelligence Hub

> An all-in-one decentralized trading intelligence platform built on [Intercom](https://github.com/Trac-Systems/intercom) by Trac Systems.

---
<img width="1309" height="844" alt="image" src="https://github.com/user-attachments/assets/68ddd88a-e11e-4f0a-923a-0ac625d770dd" />

## 🚀 What is TracSignal?

**TracSignal** is a peer-to-peer crypto trading intelligence hub where autonomous agents coordinate over Intercom sidechannels to:

- 📡 **Broadcast trading signals** (BUY / SELL / HOLD) in real-time
- 🔮 **Aggregate price oracles** from multiple agent nodes
- 📊 **Track market sentiment** via collective agent consensus
- 🌐 **Visualize the P2P mesh** of active Intercom agents
- 📟 **Log all agent activity** from the Intercom sidechain

All coordination happens via Intercom's fast P2P sidechannels. Signal consensus is written to the replicated state layer so every peer sees the same view.

---

## ✨ Features

| Feature | Description |
|---|---|
| Signal Board | Real-time BUY/SELL/HOLD signals from agents with confidence scores and voting |
| P2P Price Oracle | Live price feed aggregated across active agent nodes |
| Sentiment Tracker | Bull/Bear consensus bars updated every epoch |
| Network Nodes | Visual mesh showing online/offline agent peers |
| Agent Log | Live activity stream from the Intercom sidechain |
| Broadcast | Submit your own signal and broadcast it to all peers |

---

## 🛠 How to Run

```bash
# Clone this fork
git clone https://github.com/YOUR_USERNAME/intercom
cd intercom

# Install dependencies
npm install

# Start the Intercom node
npm start

# Open the UI
open index.html
```

The app runs directly in the browser as a static HTML file. No server needed for the frontend — it connects to your local Intercom node via WebSocket.

---

## 📸 Screenshots

> App is live and working — see `index.html` for the full interactive demo.

Features visible in the UI:
- Cyberpunk-themed dark dashboard with scanline overlay
- Live ticker tape with real-time price updates
- Signal cards with confidence bars and upvote/downvote
- P2P node visualization with animated dots
- Agent activity log with color-coded entries

---

## 🏗 Architecture

```
TracSignal App
    │
    ├── Intercom Sidechannel (fast P2P)
    │       ├── Signal negotiation
    │       ├── Agent consensus voting
    │       └── Price oracle aggregation
    │
    └── Intercom Replicated State
            ├── Final signal history
            └── Sentiment snapshots
```

---

## 💰 Trac Address

```
trac1u4dwce3qzyghg4cz3cm7ryewdnjd2rlyupc5fjj2mdn7ftx2ryvqc95cuc
```

> TNK payout for awesome-intercom inclusion should be sent to the address above.

---

## 🔗 Links

- **Upstream Intercom**: https://github.com/Trac-Systems/intercom
- **Awesome Intercom List**: https://github.com/Trac-Systems/awesome-intercom
- **Trac Systems**: https://github.com/Trac-Systems

---

## 📄 License

MIT — Fork freely, build something awesome.
