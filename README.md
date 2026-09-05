<h1 align="center">Ashutosh Jha</h1>

<p align="center">
  <b>Software Engineer @ Paytm</b> &nbsp;·&nbsp; Noida, India<br/>
  I build distributed backend systems for IoT payment devices — real-time pipelines,<br/>
  low-latency audio, and the occasional database written from scratch in C.
</p>

<p align="center">
  <a href="https://thealonemusk.vercel.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-thealonemusk.vercel.app-E35342?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://linkedin.com/in/thealonemusk"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-thealonemusk-17120E?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:ashutosh.jha.cs@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-say%20hello-83B918?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=thealonemusk&label=Profile%20views&color=E35342&style=flat-square"/>
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/thealonemusk?style=flat-square&color=E35342&labelColor=17120E"/>
</p>

---

## What I'm working on

**Paytm Soundbox** — the little speaker that announces payments at millions of Indian shopfronts.

- Distributed backend services supporting real-time transaction processing across **12+ device variants** in India and Indonesia
- Real-time **MQTT pub/sub pipelines** for RTOS devices, delivering sub-second events across the fleet
- A low-latency audio pipeline for **AI Soundbox** — phase-wise chunking, Base64 PCM buffering, a 10K-entry prefetch buffer, replacing the old AMR/MP3 path
- Root CA validation and rotation for secure device authentication at fleet scale
- An **agentic AI development pipeline** — architect, developer, reviewer and validator agents running from a single Jira ticket through to deployment, cutting planning-to-deploy from 2 weeks to 4 days

---

## Selected projects

**AI & developer tooling**

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[SysMCP](https://github.com/thealonemusk/SysMCP)** | An MCP server exposing real Linux production-debugging primitives — `perf`, `strace`, `/proc`, flamegraphs, eBPF — as safe, agent-callable tools, so an agent can diagnose *why a service is slow* instead of guessing from logs. | `Python` `MCP` `eBPF` |
| **[DriftBench](https://github.com/thealonemusk/DriftBench)** | Runs an agent through 30 sequential tickets against one growing codebase to measure context drift. Finding: retrieval recall falls **90% → 25%** across the run, and task success follows it down. | `Python` |
| **[Helix](https://github.com/thealonemusk/Helix)** | A multi-agent orchestration framework. | `Rust` |
| **[AI-CLI](https://github.com/thealonemusk/AI-CLI)** | Converts natural language into safe bash commands, with validation, sanitisation and a confirm-before-run safe mode. | `Python` |
| **[TempoApply](https://github.com/thealonemusk/TempoApply)** | Job-hunting agent: scrapes LinkedIn/Indeed/Naukri, scores roles for fit, tailors a LaTeX resume per job and drafts outreach. | `Python` `Gemini` |
| **[Memory Doctor](https://github.com/thealonemusk/mem_doc_agent)** | AI static analysis for embedded C (FreeRTOS) — tree-sitter AST extraction isolates allocation and IPC-queue code, tracking pointers as they escape into RTOS queues, then an LLM catches leaks traditional analyzers miss. | `Python` `tree-sitter` |

**Systems & infrastructure**

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[OktaDB](https://github.com/thealonemusk/OktaDB)** | A relational database engine from scratch — custom storage engine, page-based persistence, B-Tree indexing for O(log n) ops, and a SQL-like executor with predicate filtering. No external libraries. | `C` |
| **[ThrottleX](https://github.com/thealonemusk/ThrottleX)** | Rate-limiting microservice implementing Token Bucket and Sliding Window, with REST APIs built for high-throughput use and live observability of token state. | `Java` `Spring Boot` `MySQL` `Docker` |
| **[Push2Prod](https://github.com/thealonemusk/Push2Prod)** · [live](https://push2-prod.vercel.app) | Git-to-cloud deployment platform — Redis-backed task queues coordinating concurrent deploys across EC2, EKS and S3, wired to GitHub Actions. | `Node.js` `AWS` `Docker` |
| **[QuantCraft](https://github.com/thealonemusk/QuantCraft)** | Modular backtesting engine in modern C++17: data-loader → strategy → execution → portfolio, with mean-reversion and momentum strategies. | `C++17` |
| **[Encryption-Library-in-C](https://github.com/thealonemusk/Encryption-Library-in-C)** | A small RC4 encryption library written in C. | `C` |

**Applications & ML**

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[LD-Net](https://github.com/thealonemusk/LD-Net-Lightweight-Dehazing-Network)** ⭐6 | Deep-learning image/video dehazing — a PyTorch autoencoder served to a React front end through a Flask API. | `PyTorch` `CNN` `Flask` |
| **[eresource](https://github.com/thealonemusk/eresource)** ⭐3 | Decentralized energy-trading application. | `TypeScript` |
| **[SecureKey](https://github.com/thealonemusk/SecureKey)** | React Native password manager with encrypted storage and offline access. | `React Native` `MongoDB` |

<p align="center"><i><a href="https://github.com/thealonemusk?tab=repositories">…and 62 more repos</a></i></p>

---

## Toolbox

<p align="center"><img alt="Languages" src="https://skillicons.dev/icons?i=c,cpp,java,python,js,ts" /></p>
<p align="center"><img alt="Backend and data" src="https://skillicons.dev/icons?i=spring,nodejs,mysql,postgres,redis" /></p>
<p align="center"><img alt="Cloud and tooling" src="https://skillicons.dev/icons?i=aws,docker,kubernetes,githubactions,jenkins,git,linux" /></p>
<p align="center"><img alt="Frontend" src="https://skillicons.dev/icons?i=react,nextjs,tailwind" /></p>

---

## A few things I'm proud of

- 🏅 **Codeforces Expert** — rating 1676 · [profile](https://codeforces.com/profile/thealonemusk)
- 🌍 **Global Rank 109** of 40,000+ in Educational Codeforces Round 186 (Div. 2)
- 🧩 **1200+ problems** solved across LeetCode, Codeforces and GeeksforGeeks · LeetCode rating 1669
- 🚀 **Smart India Hackathon 2023** — National Finalist among 1M+ participants
- 🎓 **B.Tech CSE**, NIT Jalandhar

---

## Streak

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=thealonemusk&hide_border=true&background=00000000&stroke=E35342&ring=E35342&fire=83B918&currStreakLabel=E35342&sideLabels=C9C4BE&dates=8A7E70&currStreakNum=FFFBF5&sideNums=FFFBF5"/>
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=thealonemusk&hide_border=true&background=00000000&stroke=E35342&ring=E35342&fire=83B918&currStreakLabel=E35342&sideLabels=4A423A&dates=8A7E70&currStreakNum=17120E&sideNums=17120E"/>
    <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=thealonemusk&hide_border=true"/>
  </picture>
</p>


---

<p align="center">
  <b>Want to build something together?</b><br/>
  Whether you have a project in mind, want to collaborate, or just have a question —<br/>
  reach me at <a href="mailto:ashutosh.jha.cs@gmail.com">ashutosh.jha.cs@gmail.com</a> or book time at <a href="https://cal.com/thealonemusk">cal.com/thealonemusk</a>.
</p>

<p align="center">
  <a href="https://github.com/thealonemusk"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-17120E?style=flat-square&logo=github&logoColor=white"/></a>
  <a href="https://linkedin.com/in/thealonemusk"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-17120E?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://twitter.com/thealonemusk"><img alt="X" src="https://img.shields.io/badge/X-17120E?style=flat-square&logo=x&logoColor=white"/></a>
  <a href="https://www.leetcode.com/thealonemusk"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-17120E?style=flat-square&logo=leetcode&logoColor=white"/></a>
  <a href="https://codeforces.com/profile/thealonemusk"><img alt="Codeforces" src="https://img.shields.io/badge/Codeforces-17120E?style=flat-square&logo=codeforces&logoColor=white"/></a>
  <a href="https://instagram.com/thealonemusk"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-17120E?style=flat-square&logo=instagram&logoColor=white"/></a>
</p>
