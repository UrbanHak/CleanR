# CleanR
Rewarding Mobile Car Node 
# 🚗 CleanRide Nodes

**CleanRide Nodes** is a decentralized physical infrastructure network (DePIN) that turns clean mobility into a verifiable, rewarded event on-chain. By mounting light Web3 nodes inside vehicles, we validate eco-friendly transport data and distribute CLEAN tokens to riders and drivers.

---

## 🌍 Project Overview

This project enables:

- Web3 light clients mounted on vehicles
- Real-time GPS and vehicle data validation
- Token rewards (CLEAN) based on verified clean miles
- Smart contracts to manage incentives and staking
- A dApp interface for users to monitor activity and rewards

---

## 📁 Folder Structure

```bash
cleanride-nodes/
│
├── hardware/                # Embedded device setup, sensor drivers
│   └── raspberry-setup.md
│
├── software/
│   ├── node-client/         # Light node & validator logic (Python/Go)
│   ├── data-engine/         # Movement scoring, trip validation
│   └── api-server/          # REST APIs for dApp and backend access
│
├── smart-contracts/         # CLEAN token, reward contracts (Solidity)
│   ├── contracts/
│   └── test/
│
├── dapp/                    # Frontend dashboard (React/Next.js)
│   ├── components/
│   └── pages/
│
├── diagrams/                # Mermaid.js diagrams, SVG exports
│   └── architecture-v2.mmd
│
├── docs/                    # Whitepapers, tokenomics, technical specs
│   ├── executive-summary.md
│   └── tokenomics-model.md
│
├── scripts/                 # Deployment or testing scripts
│
├── .env.example             # Environment variable templates
├── README.md                # You're here.
└── LICENSE

