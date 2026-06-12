<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:6d28d9,100:8b5cf6&height=220&section=header&text=Enzo%20Palmisano&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%20%E2%80%A2%20AI%20Specialist%20%E2%80%A2%20Product-Minded%20Builder&descAlignY=55&descSize=18" width="100%" alt="Header banner" />

<a href="https://github.com/e-palmisano">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=8B5CF6&center=true&vCenter=true&width=650&lines=Backend+Engineer+%26+AI+Specialist;Generative+AI+%26+LLM+Systems;Native+macOS+%26+Full+Stack+Development;Building+Reliable+Enterprise+Software" alt="Typing animation" />
</a>

<br/>

<img src="https://img.shields.io/badge/Focus-Computer_Science_%26_AI-6d28d9?style=flat-square&logo=googlescholar&logoColor=white" alt="Academic focus" />
<img src="https://img.shields.io/badge/📍_Location-Bologna,_Italy-4c1d95?style=flat-square" alt="Location" />

<br/><br/>

<a href="https://www.linkedin.com/in/enzo-palmisano-b16363147/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:e.palmisano@reply.it">
  <img src="https://img.shields.io/badge/Email-6366f1?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://github.com/e-palmisano">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=e-palmisano&style=flat-square&color=8b5cf6&label=Profile+Views" alt="Profile views" />
<a href="https://github.com/e-palmisano?tab=followers">
  <img src="https://img.shields.io/github/followers/e-palmisano?style=flat-square&logo=github&color=6d28d9&label=Followers" alt="Followers" />
</a>
<a href="https://github.com/e-palmisano?tab=repositories">
  <img src="https://img.shields.io/github/stars/e-palmisano?style=flat-square&logo=github&color=8b5cf6&label=Stars" alt="Stars" />
</a>

</div>

---

## 🧭 About

Backend Engineer & AI Specialist at **Blue Reply**, working on enterprise software for the insurance domain. I design and ship backend systems and Generative AI solutions — from LLM-powered assistants to the APIs and data layers that make them production-ready.

- ⚙️ **Software Engineering** — clean architecture, protocol-oriented design, test-first development, zero-dependency native apps
- 🤖 **AI / ML** — Generative AI, LLM integration, RAG pipelines, and agentic workflows for enterprise use cases
- 🧱 **Full Stack** — backend services, REST APIs, data persistence, and the frontend surfaces that consume them
- 🚀 **Product Engineering Mindset** — I ship complete products: packaging, distribution (Homebrew), CI/CD, and documentation included

**Open To:** collaboration on open-source tooling, AI engineering projects, and conversations about native macOS development.

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,swift,ts,js,java,bash" alt="Languages" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,html,css,tailwind" alt="Frontend" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,spring,postgres,mongodb,redis" alt="Backend and databases" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=aws,docker,git,github,githubactions,linux,apple" alt="Cloud, DevOps and tooling" />

</div>

---

## 🤖 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:-------|:-----------:|:--------|
| **Generative AI & LLMs** | ▰▰▰▰▰▱ | LLM-powered assistants, prompt engineering, model integration in enterprise products |
| **RAG Systems** | ▰▰▰▰▰▱ | Retrieval pipelines, embeddings, vector search, grounded enterprise knowledge bases |
| **Agentic AI** | ▰▰▰▰▱▱ | Tool-using agents, coding-agent harnesses, multi-step orchestration |
| **NLP** | ▰▰▰▰▱▱ | Text extraction, transcription pipelines, document understanding |
| **MLOps & Serving** | ▰▰▰▱▱▱ | API-first model serving, evaluation loops, CI for ML-backed services |

</div>

---

## 🚀 Featured Projects

<details>
<summary><b>🔒 Vigil — Native macOS Input Lock</b></summary>

<br/>

A lightweight native macOS utility that blocks all physical input system-wide while keeping long-running workloads — builds, renders, downloads — fully active.

| | |
|:--|:--|
| **Stack** | Swift 6, AppKit, CGEventTap, XcodeGen |
| **Scale** | Multi-display with hot-plug detection; system-wide HID-level event interception |
| **Performance** | Fully native, zero external dependencies, no telemetry, no network calls |
| **Security** | Accessibility-gated input blocking, Touch ID unlock with password fallback, crash-recovery lock restore |
| **Impact** | Shipped end-to-end: signed releases, Homebrew cask distribution, CI pipeline |
| **Repository** | [e-palmisano/Vigil](https://github.com/e-palmisano/Vigil) |

Vigil intercepts keyboard and mouse events at the HID level — the only macOS API that blocks input before it reaches any application. The architecture is protocol-oriented (every service behind a `*Protocol` interface with test mocks), test-first, and deliberately dependency-free.

</details>

<details>
<summary><b>🧩 macos-dev — Claude Code Plugin for Native macOS Development</b></summary>

<br/>

A Claude Code plugin for native macOS development with SwiftUI, AppKit, and Liquid Glass, bundling curated Apple Developer documentation for agentic coding workflows.

| | |
|:--|:--|
| **Stack** | JavaScript, Claude Code plugin system, curated Apple Developer docs |
| **Scale** | Covers SwiftUI, AppKit, and modern macOS design-system APIs |
| **Performance** | Local documentation bundle — zero network latency for doc lookups |
| **Security** | Read-only documentation tooling, no credentials or external calls |
| **Impact** | Makes AI coding agents reliable on niche, fast-moving native macOS APIs |
| **Repository** | [e-palmisano/macos-dev](https://github.com/e-palmisano/macos-dev) |

Built from the experience of developing Vigil with AI pair programmers: agents are only as good as the context they're given, so this plugin gives them first-class, curated platform documentation.

</details>

<details>
<summary><b>🍺 homebrew-tap — Distribution Infrastructure</b></summary>

<br/>

A Homebrew tap providing one-command installation for my macOS tools.

| | |
|:--|:--|
| **Stack** | Ruby, Homebrew cask DSL, GitHub Releases |
| **Scale** | Single tap serving all published tools (`brew install --cask e-palmisano/tap/vigil`) |
| **Performance** | Automated cask updates tied to the release pipeline |
| **Security** | Checksummed artifacts pulled from signed GitHub Releases |
| **Impact** | Frictionless install path — from repository to running app in one command |
| **Repository** | [e-palmisano/homebrew-tap](https://github.com/e-palmisano/homebrew-tap) |

Shipping a product means owning distribution too: this tap closes the loop between CI builds, GitHub Releases, and the end user's machine.

</details>

<details>
<summary><b>🏢 Enterprise Generative AI Assistant — Blue Reply</b></summary>

<br/>

A Generative AI assistant developed at Blue Reply for the enterprise insurance domain.

| | |
|:--|:--|
| **Stack** | Python, LLM APIs, RAG pipeline |
| **Scale** | Enterprise knowledge base for insurance workflows |
| **Performance** | Grounded retrieval to keep responses accurate and auditable |
| **Security** | Enterprise data-handling and access controls |
| **Impact** | Brought LLM capabilities into day-to-day enterprise workflows |
| **Repository** | Private — enterprise project |

Details are confidential; happy to discuss the architecture patterns (retrieval, grounding, evaluation) in general terms.

</details>

---

## 💼 Experience

### Senior Consultant · **Blue Reply IT**

**Feb 2025 — Present** · Bologna, Italy

- Lead technical teams in the architecture and delivery of enterprise-grade solutions for insurance clients, ensuring alignment between business objectives and technology strategy
- Architect scalable backend platforms leveraging RESTful APIs, microservices, and cloud-native technologies to support high-performance business applications
- Drive Generative AI adoption and innovation, delivering custom AI solutions that enhance customer experience, streamline operations, and accelerate the Software Development Lifecycle (SDLC)

<img src="https://img.shields.io/badge/Generative_AI-8b5cf6?style=flat-square&logo=openaigym&logoColor=white" alt="Generative AI" /> <img src="https://img.shields.io/badge/REST_APIs-6366f1?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs" /> <img src="https://img.shields.io/badge/Microservices-6d28d9?style=flat-square&logo=docker&logoColor=white" alt="Microservices" /> <img src="https://img.shields.io/badge/Cloud_Native-4c1d95?style=flat-square&logo=kubernetes&logoColor=white" alt="Cloud Native" />

### Consultant · **Blue Reply IT**

**Mar 2020 — Feb 2025** · Bologna, Italy

- Architected scalable backend platforms for top-tier insurance clients, leveraging RESTful APIs and microservices architectures to deliver robust, high-performance systems
- Led the design and implementation of computer vision solutions — image recognition for claims automation, document understanding for intelligent processing, and facial recognition for secure identity verification
- Drove Generative AI innovation by delivering custom-built applications that optimize operations and elevate customer experience in the insurance domain

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/Computer_Vision-8b5cf6?style=flat-square&logo=opencv&logoColor=white" alt="Computer Vision" /> <img src="https://img.shields.io/badge/Generative_AI-6366f1?style=flat-square&logo=openaigym&logoColor=white" alt="Generative AI" /> <img src="https://img.shields.io/badge/REST_APIs-6d28d9?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs" />

### Co-Founder · **Hivergy**

**Feb 2023 — Jun 2025**

- Led the end-to-end software development of the startup's core product, taking full ownership of the technical stack from architecture to production
- Designed and implemented scalable backend systems and product infrastructure in a fast-paced environment, ensuring reliability, maintainability, and rapid iteration

<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" /> <img src="https://img.shields.io/badge/Backend_Systems-8b5cf6?style=flat-square&logo=serverless&logoColor=white" alt="Backend Systems" /> <img src="https://img.shields.io/badge/Software_Architecture-6d28d9?style=flat-square&logo=diagramsdotnet&logoColor=white" alt="Software Architecture" />

### Software Engineer · **Pertec Sistemi** (Advanced Sensing Solutions)

**Sep 2019 — Feb 2020** · Modena, Italy

- Designed and developed human–machine interaction (HMI) systems, enabling seamless integration between users and complex industrial environments
- Performed advanced analysis of multi-source sensor data (IoT and industrial systems), including real-time data processing, anomaly detection, and performance optimization through data-driven insights

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/IoT_%26_Sensor_Data-8b5cf6?style=flat-square&logo=thethingsnetwork&logoColor=white" alt="IoT and sensor data" /> <img src="https://img.shields.io/badge/HMI_Systems-6d28d9?style=flat-square&logo=siemens&logoColor=white" alt="HMI Systems" />

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|:------------|:--------|
| 🚀 **Shipped a complete native macOS product** | Vigil — from architecture to signed releases, CI, and Homebrew distribution |
| 🧩 **Published developer tooling for AI agents** | macos-dev Claude Code plugin with curated Apple Developer documentation |
| 🍺 **Maintainer of a public Homebrew tap** | One-command install pipeline for all published tools |
| 🤖 **Enterprise Generative AI delivery** | LLM-powered assistant built for the insurance domain at Blue Reply |

</div>

---

## 📜 Certifications

<div align="center">

**AWS**

<img src="https://img.shields.io/badge/AWS-Certified_Solutions_Architect-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Solutions Architect" />

**MongoDB**

<img src="https://img.shields.io/badge/MongoDB-SI_Associate_Certification-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB SI Associate Certification" />

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=e-palmisano&show_icons=true&hide_border=true&bg_color=0d1117&title_color=8b5cf6&icon_color=8b5cf6&text_color=c9d1d9&ring_color=6d28d9&count_private=true" height="170" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=e-palmisano&layout=compact&hide_border=true&bg_color=0d1117&title_color=8b5cf6&text_color=c9d1d9&langs_count=8" height="170" alt="Top languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=e-palmisano&hide_border=true&background=0d1117&ring=8b5cf6&fire=a78bfa&currStreakLabel=8b5cf6&sideLabels=c9d1d9&currStreakNum=ffffff&sideNums=ffffff&dates=8b949e" alt="GitHub streak" />

</div>

---

## 🏅 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=e-palmisano&theme=dracula&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="GitHub trophies" />

</div>

---

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=e-palmisano&bg_color=0d1117&color=a78bfa&line=6366f1&point=8b5cf6&area=true&area_color=4c1d95&hide_border=true" width="95%" alt="Contribution activity graph" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/e-palmisano/e-palmisano/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/e-palmisano/e-palmisano/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/e-palmisano/e-palmisano/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake animation" />
</picture>

</div>

---

## 🎯 Current Focus

```yaml
learning:
  - Swift 6 strict concurrency and modern AppKit/SwiftUI patterns
  - Agentic AI architectures and coding-agent tooling

building:
  - Vigil — native macOS input-lock utility
  - macos-dev — Claude Code plugin for native macOS development

exploring:
  - LLM evaluation and grounding techniques for enterprise RAG
  - Developer-experience tooling for AI-assisted workflows

open_to:
  - Open-source collaboration
  - AI engineering and native macOS conversations
```

---

## 🤝 Connect

<div align="center">

<a href="mailto:e.palmisano@reply.it">
  <img src="https://img.shields.io/badge/Email-e.palmisano@reply.it-6366f1?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<br/>
<a href="https://www.linkedin.com/in/enzo-palmisano-b16363147/">
  <img src="https://img.shields.io/badge/LinkedIn-Enzo_Palmisano-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<br/>
<a href="https://github.com/e-palmisano">
  <img src="https://img.shields.io/badge/GitHub-e--palmisano-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>

---

<div align="center">

*Good tools make good work possible.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,50:6d28d9,100:4c1d95&height=120&section=footer" width="100%" alt="Footer banner" />

</div>
