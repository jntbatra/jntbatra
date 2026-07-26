<!-- HEADER -->
<a href="https://github.com/jntbatra">
  <img width="100%" src="https://raw.githubusercontent.com/jntbatra/jntbatra/master/assets/header-nothing-white.png" alt="Jayant Batra" />
</a>

<!-- TYPING SUBTITLE -->
<p align="center">
  <a href="https://github.com/jntbatra">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=26D0CE&center=true&vCenter=true&width=620&lines=Backend+%26+Systems+Engineer;Payments+%E2%80%A2+Delivery+%E2%80%A2+Scale;C%2B%2B+%7C+TypeScript+%7C+Python+%7C+375%2B+DSA+solved;Open+to+SDE+roles" alt="typing" />
  </a>
</p>

<!-- SOCIALS + VIEWS -->
<p align="center">
  <a href="https://linkedin.com/in/jntbatra"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://leetcode.com/u/jayantbatra"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://codeforces.com/profile/jayantbtra"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"></a>
  <a href="https://www.codechef.com/users/jntbatra"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"></a>
  <a href="mailto:jayantbtra@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://komarev.com/ghpvc/?username=jntbatra&label=Profile+views&color=0e75b6&style=for-the-badge" alt="views">
</p>

## `~/whoami`

I build backend systems where **correctness, latency, and cost** all matter at
once: payments that can't double-charge, caches that make screens feel instant,
infra that scales without burning money.

```ts
const jayant: Engineer = {
  education: "Computer Engineering @ Thapar '27",
  building:  "Cravo — payments-integrated food delivery (live on iOS + Android)",
  focus:     ["distributed systems", "payments infra", "GPU compute", "applied AI"],
  languages: ["C++", "TypeScript", "Python", "Go"],
  dsa:       "375+ solved on LeetCode",  // live breakdown below
  reach:     "jayantbtra@gmail.com",
};
```

## `~/projects`

**[Cravo](https://cravo-backend.jayantb.dev/app)** — food-delivery app, live on the App Store and Play Store
I built the backend end to end: 36 domains, 340+ routes, and Razorpay payments with idempotent webhooks plus a reconciliation job that treats the gateway as the source of truth, so no order double-charges. It's handled 1,500+ users and 2,500+ orders so far.
`TypeScript` · `Node` · `PostgreSQL` · `Redis` · `AWS`

**[American Option Pricing Engine](https://github.com/jntbatra/American-Option-Pricing-Engine)** — Monte Carlo options pricer on the GPU
Started out reproducing a finance paper and found its pricing method was 56% off. Rebuilt it with Longstaff-Schwartz — it now matches the Black-Scholes value to 1e-5 — and got it running 53× faster than a serial CPU baseline (10× over 28-thread OpenMP).
`C++` · `CUDA` · `OpenMP`

**[TactileSight](https://github.com/jntbatra/TactileSight-litertlm)** — letting blind users feel what's around them
A depth camera drives a 21-cell grid of vibration motors, so an obstacle becomes something you feel on your skin rather than something a cane has to find. Recognition (Qwen3-VL + YOLOv11) runs on-device on a Qualcomm NPU. Won the Multi-Device track at the Qualcomm hackathon.
`Kotlin` · `C++` · `STM32` · `on-device VLM`

**[Expense Tracker OCR](https://github.com/jntbatra/ocr-aws)** — snap a receipt, get it logged
Point a camera at a receipt and it gets read and filed automatically. OCR runs on AWS, Next.js on the front end, shipped with Docker and Terraform.
`TypeScript` · `Next.js` · `AWS` · `Docker`

**[DocPilot](https://github.com/jntbatra/DocPilot)** — a docs assistant that connects the dots
Builds a knowledge graph out of a doc set and walks it (BFS) to answer questions that span several pages — the kind plain RAG tends to miss.
`Python` · `MiniLM` · `Gemini`

**[Homelab](https://github.com/jntbatra/Homelab-Infrastructure-Engineering)** — my whole homelab, kept as code
k3s with Argo CD that self-heals, Prometheus and Grafana watching it, and Terraform for the VMs. `make rebuild` brings the whole thing back from nothing — which I wrote after a host reset wiped the hand-built version and taught me the lesson.
`K3s` · `Terraform` · `Argo CD` · `Prometheus`

## `~/stack`

**Languages**
<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white">
</p>

**Backend & Data**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=google&logoColor=white">
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
</p>

**Cloud & DevOps**
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
</p>

## `~/highlights`

- 🥇 **Winner**: Qualcomm Global Multiverse Hackathon (Multi-Device Track, Top 8)
- 🌏 **International Finalist**: TRON Hackathon, Japan
- 🧩 **375+** DSA problems solved on LeetCode (live count below)

## `~/leetcode`

<p align="center">
  <a href="https://leetcode.com/u/jayantbatra">
    <img src="https://leetcard.jacoblin.cool/jayantbatra?theme=dark&font=Baloo%202" alt="LeetCode stats" />
  </a>
</p>

## `~/activity`

<div align="center">
  <img height="165" src="https://github-readme-stats-cyan-tau-85.vercel.app/api?username=jntbatra&show_icons=true&hide_rank=true&count_private=true&include_all_commits=true&hide_border=true&theme=tokyonight&cache_seconds=86400" alt="stats" />
  <img height="165" src="https://github-readme-stats-cyan-tau-85.vercel.app/api/top-langs/?username=jntbatra&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" alt="top langs" />
</div>

<!-- SNAKE (auto-generated by .github/workflows/snake.yml) -->
<div align="center">
  <img src="https://raw.githubusercontent.com/jntbatra/jntbatra/output/github-snake-dark.svg" alt="snake animation" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jntbatra&hide_border=true&area=true&theme=tokyo-night" alt="commit activity graph" />
</div>

## `~/badges`

<p align="center"><b>Hacktoberfest 2024: Levels 0 → 4 🎉</b></p>
<p align="center">
  <a href="https://www.holopin.io/hacktoberfest2024/userbadge/cm1xmfodc142560cl18l8py81g"><img src="https://assets.holopin.io/hf2024levels/level0-sloth-hello-0-0-0-0.webp" height="110" alt="Hacktoberfest 2024: Registered" /></a>
  <a href="https://www.holopin.io/hacktoberfest2024/userbadge/cm2liaz7958410clasw1mwowp"><img src="https://assets.holopin.io/hf2024levels/level1-sloth-hello-tea-0-0-0.webp" height="110" alt="Hacktoberfest 2024: Level 1" /></a>
  <a href="https://www.holopin.io/hacktoberfest2024/userbadge/cm2zpapvi110300cjzor181rfu"><img src="https://assets.holopin.io/hf2024levels/level2-sloth-hello-tea-robe-0-0.webp" height="110" alt="Hacktoberfest 2024: Level 2" /></a>
  <a href="https://www.holopin.io/hacktoberfest2024/userbadge/cm310asj306400cmllmtwa1ku"><img src="https://assets.holopin.io/hf2024levels/level3-sloth-hello-tea-robe-witch-0.webp" height="110" alt="Hacktoberfest 2024: Level 3" /></a>
  <a href="https://www.holopin.io/hacktoberfest2024/userbadge/cm310asg206340cml9xhykivy"><img src="https://assets.holopin.io/hf2024levels/level4-sloth-hello-tea-robe-witch-moon.webp" height="110" alt="Hacktoberfest 2024: Level 4" /></a>
</p>

<img width="100%" src="https://raw.githubusercontent.com/jntbatra/jntbatra/master/assets/footer.png" alt="building systems that scale" />
