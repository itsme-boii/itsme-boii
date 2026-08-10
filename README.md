```bash
    .--.           Tushar@IIT
   |o_o |          ───────────────────────────────────────────────
   |:_/ |          host    : IIT Kharagpur  ·  Dual Degree  ·  8.85 CGPA
  //   \ \         role    : Backend & Distributed Systems Engineer
 (|     | )        uptime  : 3+ years shipping production backends
/'\_   _/`\        shell   : zsh + tmux, nvim is home
\___)=(___/        stack   : Rust  ·  Go  ·  Redis  ·  Postgres  ·  Blockchain
                   doing   : matching engines, schedulers, settlement pipelines
                   motto   : correct first, then fast, then scalable
```

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white" />
</p>

---

### who am I

I build backends where downtime costs money and a dropped message means broken state. Matching engines that respond in single-digit milliseconds. Distributed schedulers that recover from node failures without duplicating work. Settlement systems that keep on-chain and off-chain state consistent across 17 networks.

The parts I enjoy most are the hard parts: concurrency bugs that only show up under load, race conditions hiding behind eventual consistency, and making systems degrade gracefully instead of exploding.

---

### what I've shipped (professionally)

| where | what I built | stack |
|-------|-------------|-------|
| **Arcane Labs** (Founding Eng) | CLOB matching engine, real-time order book, multi-chain settlement infra, transaction state machines | Rust, Go, Redis, Solidity, Solana |
| **AirRender** (Backend Eng) | Distributed GPU job scheduler, fault recovery for spot instances, 5+ TB asset pipelines | Go, AWS, Azure, Cloudflare R2 |
| **ZkAGI** (Backend Eng) | Distributed GPU orchestration platform, P2P communication layer, Kubernetes deployments | Rust, K8s, Docker |

<details>
<summary><b>some numbers from production</b></summary>
<br>

- 8 to 15ms median order latency on the matching engine
- ~40% reduction in p95 API response time after pipeline rebuild
- 100+ concurrent GPU jobs dispatched across 50+ nodes
- 95%+ automatic recovery rate on preempted spot instances
- 17 blockchain networks synchronized through one reconciliation system
- 5+ TB of render assets flowing through concurrent upload pipelines

</details>

---

### stuff I've built on the side

<table>
<tr>
<td width="50%" valign="top">

#### 💸 [EMEI: Payments Infra](#)
`Rust`

Payments backend with on-chain settlement. The interesting problem was nonce race conditions on concurrent transactions. Fixed it with row-level locking and idempotent submission pipelines.

</td>
<td width="50%" valign="top">

#### 📝 [Code Collaboration Platform](#)
`Rust` `CRDTs` `WebSockets` `Redis`

Real-time collaborative editor where edits never conflict. Built on CRDTs with cross-instance room management. Handles client reconnection and document recovery on dropped sessions.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💬 [WhatsApp Backend](#)
`Rust` `Axum` `WebSockets` `MongoDB`

Full messaging backend: async delivery, offline message queue, read receipts, media upload, auth, DMs and groups. All in Rust with Axum.

</td>
<td width="50%" valign="top">

#### 🥇 [Aptos Blockchain Challenge](#)
`Move` · **Gold, InterIIT 12.0**

Move smart contracts for on-chain governance and proposal systems. Optimized gas costs by reworking the storage layout. Team took gold at InterIIT.

</td>
</tr>
</table>

---

### daily drivers

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<sub>Also: gRPC, Protocol Buffers, event-driven design, distributed locking, worker pools, pub/sub, caching strategies, observability (tracing, structured logging, metrics)</sub>

---

### how I think about systems

```
                  ┌─────────────────────────────────────────┐
                  │                                         │
                  │   1. Make it correct                    │
                  │   2. Make it observable                 │
                  │   3. Make it fast                       │
                  │   4. Make it recoverable                │
                  │   5. Then worry about scale             │
                  │                                         │
                  └─────────────────────────────────────────┘
```

I don't start with "how do we handle 10k requests per second." I start with "what happens when this crashes halfway through a write." If the failure mode is clean, the system usually scales fine once you throw hardware at it. If the failure mode is broken state, no amount of horizontal scaling saves you.

---

### a peek at my commits

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itsme-boii/itsme-boii/output/github-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/itsme-boii/itsme-boii/output/github-snake.svg" />
</picture>

</div>

---

### say hi

Building trading infra, real-time systems, or distributed backends? Always down to talk shop.

<p align="center">
  <a href="https://www.linkedin.com/in/tushar-khokhar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:tusharkhokhar.iit@gmail.com"><img src="https://img.shields.io/badge/Email-1f6feb?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/itsme-boii"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center">
  <sub>Yes, I built all of this while doing a dual degree. No, I don't sleep much.</sub>
</p>
