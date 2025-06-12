# CAPP: Contextual Authentication Presentation Protocol

> 📦 Official repository: [hopae-official/capp-spec](https://github.com/hopae-official/capp-spec)

CAPP is a lightweight, context-aware, zero-interaction protocol for presenting verifiable credentials (VCs) in physical environments like buildings, transit systems, and events. It enables fast, frictionless, one-step authentication without requiring challenge-response flows or manual user consent.

---

## ✨ Key Features

- **Pre-Consented Disclosure**: Based on holder-configured consent profiles
- **Verifier-Optional Mode**: No real-time challenge required
- **Offline/Passive Trigger**: NFC, QR, BLE or context signals
- **Minimal Disclosure**: Purpose-bound, ephemeral, and pseudonymous
- **Edge Ready**: Fully local, no live server lookup required

---

## 🔄 Protocol Flow

1. **Preparation**: Holder creates CAPP-ready VP with claims and consent profile
2. **Trigger**: Device detects NFC/QR/URI signal from verifier
3. **Consent Match**: Device matches stored profile (e.g., purpose, location, time)
4. **Auto-Present**: VP sent over HTTPS/DIDComm to verifier endpoint

---

## 🧪 Get Started

1. Clone repo
```bash
git clone https://github.com/hopae-official/capp-spec
cd capp-spec
```
2. Run verifier demo
```bash
node src/capp-verifier-server.js
```
3. Open example in browser and scan QR / tap NFC

---

## 📜 License
MIT © 2025 Hopae Inc.

---

## 🤝 Contributions
Please see [CONTRIBUTING.md](CONTRIBUTING.md) for how to get involved
