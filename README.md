# 🛠️ Decentralized Freelance Marketplace

## 🚀 Overview

A decentralized freelance platform built on the **Cardano blockchain**, enabling **secure payments** and **transparent job agreements** via smart contracts.  
Users can either **offer Services** or **post Requests**.  
Payments are locked in smart contracts and released upon **milestone approvals**.  
Authentication is **wallet-based**, ensuring trustless, peer-to-peer transactions without intermediaries.

## 💡 Why This Project Matters

In the real world, trust between clients and freelancers is often difficult to establish — especially in high-stakes or long-term projects. Consider these all-too-common scenarios:

- A construction worker builds an entire house, only to discover the client **can't (or won't) pay**.
- A freelancer completes a job and then has to **chase payments** or **negotiate compensation** after the fact.
- Clients hesitate to pay upfront, fearing **low-quality work** or **missed deadlines**.

These situations create friction, mistrust, and financial loss on both sides.

This decentralized freelance marketplace solves those issues by introducing **smart contract-backed job agreements**:

- 💰 **Funds are locked in advance**, ensuring the client has the means to pay.
- 📈 **Milestone-based payouts** allow freelancers to get paid progressively, as work is delivered and approved.
- 🛡️ **Dispute resolution mechanisms** help protect both parties in case of disagreements.

By automating trust through blockchain and removing reliance on third-party intermediaries, this platform empowers both freelancers and clients to work together with **confidence, transparency, and fairness**.


## 🧰 Tech Stack

- **Frontend:** React + TypeScript  
- **Backend:** Python + FastAPI + Poetry | Rust + Axum + Tokio
- **Smart Contracts:** Aiken (for on-chain logic)  
- **Wallet Integration:** MeshJS (supports Eternl, Nami, Flint, Gero, Lace)  
- **Blockchain APIs:** Cardano-Node, Ogmios, Blockfrost, Cardano-Submit-API
- **Database:** PostgreSQL, MongoDB  
- **File Storage:** AWS S3 (with Localstack for local development)  
- **Caching:** Redis  

---

## ✨ Features

### 👥 Users & Jobs
- Users can create **Services** that others can order.
- Alternatively, users can post **Requests** and receive proposals from freelancers.

### 🤝 Job Agreements & Milestone Payments
- Both parties agree on project terms.
- **Milestones** define payment checkpoints.
- Funds are locked in a smart contract and released when both parties approve progress.
- The remaining balance is released upon project completion.

### ⚖️ Dispute Resolution
- If disagreements arise, funds remain locked.
- Arbitration (via decentralized governance) can resolve disputes fairly.

### 🔐 Authentication via Cardano Wallets
- Integrated with **MeshJS** for seamless wallet login.
- Supports the following wallets:
  - [Eternl](https://eternl.io)
  - [Nami](https://namiwallet.io)
  - [Flint](https://flintwallet.io)
  - [Gero](https://gerowallet.io)
  - [Lace](https://www.lace.io)


## 🧪 Documentation

To see more information consult :
- [**Install Tutorial**](documentation/cookbook.md)
- [**Technical Documentation**](documentation/technical-specs.md)
---

## 🔗 Useful Links

- [Aiken Documentation](https://aiken-lang.org)  
- [FastAPI Docs](https://fastapi.tiangolo.com)  
- [React Docs](https://react.dev)  
- [MeshJS Wallet Integration](https://meshjs.dev)  
- [Blockfrost API](https://blockfrost.io)

---

## 📄 License

This project is licensed under the **MIT License**.
