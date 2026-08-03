<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:1a1a2e,100:4f48d6&text=Simon%20Pukhov&fontSize=58&fontColor=ffffff&fontAlignY=40&desc=Senior%20Full-Stack%20Engineer%20%C2%B7%207%2B%20years&descSize=20&descAlignY=60" alt="Simon Pukhov — Senior Full-Stack Engineer" />

<div align="center">

<a href="LINKEDIN_URL"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="TELEGRAM_URL"><img src="https://img.shields.io/badge/Telegram-Message-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>&nbsp;
<a href="mailto:semyenpukhov@gmail.com"><img src="https://img.shields.io/badge/Email-Write%20me-e3a13c?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
<img src="https://img.shields.io/badge/Open%20to-Senior%20Full--Stack%20roles-4cc796?style=for-the-badge" alt="Open to work" />

</div>

<br/>

I build product systems end to end: the interface people use, the APIs and
background jobs behind it, and the operational details that keep it fast and
affordable. Led a ~6-person cross-functional team; launched startup products
that reached production, real users, and revenue. AI-native workflow: I ship
daily with Claude Code and agent pipelines, and build LLM features as an
engineer — cost tracking, retries, and provider abstraction included.

## 🛠 Stack

<div align="center">
  <a href="#"><img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,nodejs,python,fastapi,postgres,redis,aws,docker,githubactions&perline=12" alt="Tech stack icons" /></a>

  <br/><br/>

  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/AI%20Agents-4f48d6?style=for-the-badge" alt="AI Agents" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LLM%20APIs-e3a13c?style=for-the-badge" alt="LLM APIs" />
  <img src="https://img.shields.io/badge/WebSockets-333?style=for-the-badge" alt="WebSockets" />

</div>

## 🚀 Featured builds

| | Project | What it demonstrates | CI |
| :-- | :-- | :-- | :-- |
| 💬 | [**RelayDesk**](https://github.com/SemyenPukhov/relaydesk) | Realtime support inbox — WebSocket gateway, optimistic sends with idempotent retries, presence, RBAC, audit trail | ![CI](https://github.com/SemyenPukhov/relaydesk/actions/workflows/ci.yml/badge.svg) |
| 🤖 | [**FlowPilot**](https://github.com/SemyenPukhov/flowpilot) | LLM workflow engine — provider abstraction, retries with jittered backoff, token accounting, per-run cost budgets | ![CI](https://github.com/SemyenPukhov/flowpilot/actions/workflows/ci.yml/badge.svg) |
| 📊 | [**CostLens**](https://github.com/SemyenPukhov/costlens) | Cloud-cost intelligence dashboard — typed domain logic, anomaly detection, Docker, tests, polished responsive UI | ![CI](https://github.com/SemyenPukhov/costlens/actions/workflows/ci.yml/badge.svg) |
| 🎬 | **StreamForge** · *in progress* | Media pipeline — processing jobs, CDN-aware delivery, performance instrumentation | |

> Portfolio projects are independent demos with fictional data — they show how
> I work without exposing NDA-protected products or customers.

<table>
  <tr>
    <td width="50%">
      <a href="https://github.com/SemyenPukhov/relaydesk">
        <img src="https://raw.githubusercontent.com/SemyenPukhov/relaydesk/main/docs/inbox-dark.png" alt="RelayDesk — realtime support inbox" />
      </a>
      <p align="center"><sub><b>RelayDesk</b> — realtime inbox with presence, optimistic sends, and audit trail</sub></p>
    </td>
    <td width="50%">
      <a href="https://github.com/SemyenPukhov/flowpilot">
        <img src="https://raw.githubusercontent.com/SemyenPukhov/flowpilot/main/docs/flowpilot-light.png" alt="FlowPilot — LLM workflow engine" />
      </a>
      <p align="center"><sub><b>FlowPilot</b> — LLM pipelines with cost budgets and per-step token accounting</sub></p>
    </td>
  </tr>
</table>

## 📈 Measurable engineering impact

<div align="center">
<table>
  <tr>
    <td align="center" width="25%"><h3>~1.5×</h3><sub>AWS cost reduction<br/>(regions, Lambda, CloudFront)</sub></td>
    <td align="center" width="25%"><h3>-$3,000/mo</h3><sub>Twitter/X API<br/>cost reduction</sub></td>
    <td align="center" width="25%"><h3>4s → 1.5s</h3><sub>video player<br/>initial load</sub></td>
    <td align="center" width="25%"><h3>~$600</h3><sub>LLM token-spend<br/>reduction*</sub></td>
  </tr>
</table>
<sub>*period unspecified</sub>
</div>

## 🧩 Engineering notes & snippets

| Area | Snippets |
| :-- | :-- |
| ⚛️ React | [Debounced async search without race conditions](https://gist.github.com/SemyenPukhov/92f1e509d2277dbcb4b271c23e37fc66) · [Optimistic mutation hook with rollback](https://gist.github.com/SemyenPukhov/48d6a2cb7e78bdb91d1d56b6ee7338b0) |
| 🟢 Node.js | [Bounded-concurrency promise pool](https://gist.github.com/SemyenPukhov/2f048184c2c03cb41d2dd31ff46ae984) · [Graceful shutdown with cleanup timeout](https://gist.github.com/SemyenPukhov/6aeca6844ff1403c85f3b6f0ee14a103) |
| 🔷 TypeScript | [Retry with capped backoff + jitter](https://gist.github.com/SemyenPukhov/be05be3d1940fa3b8a750146dd53e5a9) · [Fail-fast env validation with Zod](https://gist.github.com/SemyenPukhov/8d84d7c5878735e86357b0ede9bba62d) · [Typed event bus](https://gist.github.com/SemyenPukhov/467f759fb5e3c46ba3a2c1ce9ae31cbb) |
| 🐍 Python | [LLM spend guard with budget ceiling](https://gist.github.com/SemyenPukhov/367da69eb0e68ffcfe0fd185b084adaa) · [FastAPI request-id middleware](https://gist.github.com/SemyenPukhov/14aa338dfe2dd8aadbf1936b0d11c2f4) |
| ☁️ Infra | [Atomic Redis sliding-window rate limiter](https://gist.github.com/SemyenPukhov/c9a4ea5ac2a85a35a7efa2f4efe2bf79) · [AWS Lambda cost review checklist](https://gist.github.com/SemyenPukhov/d1e28c674df5d2cd5298f408f1432f2d) · [Next.js cache boundary with auth](https://gist.github.com/SemyenPukhov/6e9e4229103ac3d3473d226c38c59117) |

## 📊 GitHub

<div align="center">

<img src="https://streak-stats.demolab.com?user=SemyenPukhov&hide_border=true&background=00000000&ring=e3a13c&fire=e3a13c&currStreakLabel=e3a13c&sideLabels=9c9aab&sideNums=eceaf0&currStreakNum=eceaf0&dates=6d6b7c" alt="Contribution streak" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SemyenPukhov/SemyenPukhov/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/SemyenPukhov/SemyenPukhov/output/github-snake.svg" alt="Contribution snake" />
</picture>

</div>

## 📫 Contact

<div align="center">

Open to **Senior Full-Stack Engineer** roles — Europe · US · Cyprus · remote-first teams.

<a href="LINKEDIN_URL"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="TELEGRAM_URL"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>&nbsp;
<a href="mailto:semyenpukhov@gmail.com"><img src="https://img.shields.io/badge/semyenpukhov@gmail.com-e3a13c?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:e3a13c,50:4f48d6,100:0b0d13&section=footer" alt="" />
