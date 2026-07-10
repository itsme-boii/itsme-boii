<div align="center">

# Tushar Khokhar

### Backend & Distributed Systems Engineer

<a href="https://github.com/itsme-boii">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=640&lines=backend+is+home%2C+the+terminal+is+my+IDE;Go%2C+Rust+and+a+whole+lot+of+distributed+systems;chasing+tail+latencies+since+forever;yes%2C+I+use+Linux+btw" />
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/tushar-khokhar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/itsme-boii"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="mailto:tusharkhokhar.iit@gmail.com"><img src="https://img.shields.io/badge/Email-1f6feb?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

---

```bash
    .--.           tushar@kharagpur
   |o_o |          ───────────────────────────────────────────────
   |:_/ |          host    : IIT Kharagpur  ·  B.Tech (8.85 CGPA)
  //   \ \         role    : Backend & Distributed Systems Engineer
 (|     | )        uptime  : 3+ years shipping production backends
/'\_   _/`\        shell   : zsh + tmux, and nvim always open
\___)=(___/        stack   : Go  ·  Rust  ·  TypeScript  ·  Linux
                   doing   : matching engines, schedulers, pipelines
                   motto   : correct first, then fast, then scalable
```

I basically live in your terminal. Most of my work is backends that have to stay up under load: matching engines, distributed schedulers, real-time pipelines, that kind of thing. The parts I actually enjoy are the annoying ones, concurrency, keeping data consistent, chasing down latency, and making sure things fail quietly instead of taking everything down with them.

---

### the impact

<table>
<tr>
<td align="center" width="20%">

## 40%
<sub>lower p95 latency</sub>

</td>
<td align="center" width="20%">

## 3K
<sub>orders/sec matched</sub>

</td>
<td align="center" width="20%">

## 200GB+
<sub>asset pipelines</sub>

</td>
<td align="center" width="20%">

## 100K+
<sub>requests served</sub>

</td>
<td align="center" width="20%">

## 3+ yrs
<sub>shipping backends</sub>

</td>
</tr>
</table>

---

### things I build with

<table>
<tr>
<td valign="top" width="50%">

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=google&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

</td>
<td valign="top" width="50%">

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

</td>
</tr>
</table>

**Daily drivers**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<sub>Also comfy with: event-driven design, worker pools, distributed locking, pub/sub, caching, and the observability side of things.</sub>


### stuff I've built on the side

<!-- swap the # links for your real repos -->

<table>
<tr>
<td width="50%" valign="top">

#### 💸 [EMEI, Payments Infra](#)
`Rust`

A Rust backend for payments and on-chain settlement. The fun bug here was nonce race conditions, killed with row-level locking so concurrent transactions stop stepping on each other.

</td>
<td width="50%" valign="top">

#### 📝 [Code Collaboration Platform](#)
`Rust` `CRDTs` `WebSockets` `Redis`

A real-time collaborative editor built on CRDTs, so edits never conflict. Handles rooms across instances and can bring a document back if a client drops mid-session.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💬 [WhatsApp Backend](#)
`Rust` `Axum` `WebSockets` `MongoDB`

A messaging backend in Rust. Does async delivery, offline storage, read receipts, auth and media, for both DMs and groups.

</td>
<td width="50%" valign="top">

#### 🥇 [Aptos Blockchain Challenge](#)
`Move` · Gold, InterIIT 12.0

Move contracts for on-chain governance and proposals. Spent way too long trimming gas by reworking the storage layout. Team took gold.

</td>
</tr>
</table>

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

Building trading infra, real-time systems or distributed backends? I'm always down to talk shop.

<a href="https://www.linkedin.com/in/tushar-khokhar/"><img src="https://img.shields.io/badge/Ping%20me%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:tusharkhokhar.iit@gmail.com"><img src="https://img.shields.io/badge/Drop%20a%20mail-1f6feb?style=for-the-badge&logo=gmail&logoColor=white" /></a>
