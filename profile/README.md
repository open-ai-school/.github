<div align="center">

# 🎓 Open AI School

### Free, open-source, multilingual AI education for everyone

[![Website](https://img.shields.io/badge/Website-open--ai--school.vercel.app-0071e3?style=for-the-badge&logo=vercel&logoColor=white)](https://open-ai-school.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-30d158?style=for-the-badge)](https://github.com/open-ai-school/ai-seeds/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/open-ai-school/ai-seeds?style=for-the-badge&color=ff9f0a)](https://github.com/open-ai-school/ai-seeds)
[![Discussions](https://img.shields.io/badge/Discussions-Join%20Us-purple?style=for-the-badge&logo=github)](https://github.com/open-ai-school/ai-seeds/discussions)

---

**Learn AI from zero — no coding experience, no math degree, no jargon.**

🌍 Available in **English** · **Français** · **Nederlands** · **हिन्दी** · **తెలుగు** · *more coming soon!*

</div>

## 🌱 Our Mission

We believe AI education should be **free**, **accessible**, and **available in your language**. Too many learners — especially in India and the Global South — are left behind because quality AI resources are in English, behind paywalls, or assume prior technical knowledge.

Open AI School changes that. We start from the very basics and build understanding step by step, using everyday language and real-world analogies.

## 📚 What We Offer

| | Feature | Description |
|---|---|---|
| 🌱 | **Beginner-First** | No prerequisites — we start from "What is AI?" |
| 🌍 | **Multilingual** | Content in 5+ languages and growing |
| 🧪 | **Interactive** | Hands-on AI Playground with TensorFlow.js |
| 💝 | **100% Free** | No paywalls, no subscriptions, ever |
| 🔓 | **Open Source** | All code and content on GitHub |
| 📱 | **Mobile Friendly** | Learn on any device |

## 🤖 Automated Workflow Pipeline

All repos in this org use a fully automated GitHub Actions pipeline. When you open an issue, bots handle triage, planning, sub-issue creation, PR drafting, code review, and cleanup — so contributors can focus on code.

```mermaid
flowchart TD
    A["🆕 Issue Opened"] --> B["🏷️ Triage Bot"]
    B -->|"auto-labels, priority P0-P3, size"| C{"Maintainer adds\n'needs-plan' label"}
    C --> D["📋 Planner Bot"]
    D -->|"generates implementation\nplan as comment"| E{"Maintainer adds\n'planned' label"}
    E --> F["👹 Issue Monster"]
    F -->|"creates linked\nsub-issues from plan"| G{"Maintainer adds\n'ready-for-dev' label"}
    G --> H["🚀 Draft PR Creator"]
    H -->|"creates branch +\ndraft PR"| I["👩‍💻 Human pushes code"]
    I --> J["Marks PR Ready for Review"]
    J --> K["🔍 Auto-Review Bot"]
    K -->|"size labels, test check,\nwarnings posted"| L{"Maintainer approves PR"}
    L --> M["✅ Merge Helper"]
    M -->|"labels 'ready-to-merge'"| N["👩‍💻 Human merges"]
    N --> O["🔗 Sub-issue Closer"]
    O -->|"closes linked issues\nvia 'Closes #N'"| P["🎯 Plan Closer"]
    P -->|"closes parent issue when\nall sub-issues done"| Q["✨ Done!"]

    R["⏰ Weekly Cron"] --> S["🧹 Stale Bot"]
    S -->|"marks stale after 30d\ncloses after 14 more"| T["Keeps backlog clean"]

    U["🆕 First-time Contributor"] --> V["👋 Welcome Bot"]
    V -->|"welcome message +\nguidance"| W["Contributor feels at home"]

    style A fill:#4CAF50,color:#fff
    style Q fill:#4CAF50,color:#fff
    style B fill:#2196F3,color:#fff
    style D fill:#2196F3,color:#fff
    style F fill:#FF5722,color:#fff
    style H fill:#9C27B0,color:#fff
    style K fill:#FF9800,color:#fff
    style M fill:#4CAF50,color:#fff
    style O fill:#607D8B,color:#fff
    style P fill:#607D8B,color:#fff
    style S fill:#795548,color:#fff
    style V fill:#E91E63,color:#fff
```

### Workflow Details

| Bot | Trigger | What it does |
|-----|---------|-------------|
| 🏷️ **Triage** | Issue opened | Auto-labels (`bug`, `feature`, `docs`), sets priority (`P0`–`P3`), adds size label |
| 📋 **Planner** | `needs-plan` label | Generates step-by-step implementation plan as a comment |
| 👹 **Issue Monster** | `planned` label | Parses plan checklist, creates linked sub-issues |
| 🚀 **Draft PR Creator** | `ready-for-dev` label | Creates feature branch + draft PR linked to issue |
| 🔍 **Auto-Review** | PR ready for review | Posts size stats, checks for tests/docs, adds warnings |
| ✅ **Merge Helper** | PR approved + checks pass | Labels `ready-to-merge` for human to merge |
| 🔗 **Sub-issue Closer** | PR merged | Closes issues referenced with `Closes #N` |
| 🎯 **Plan Closer** | Sub-issue closed | Closes parent when all sub-issues are done |
| 🧹 **Stale Bot** | Weekly cron | Marks inactive issues/PRs stale, closes after 14 days |
| 👋 **Welcome Bot** | First issue/PR | Welcomes new contributors with guidance |

> 💡 All workflows use **concurrency groups** with `cancel-in-progress: true` — new commits automatically cancel outdated runs.

## 🚀 Get Started

Visit **[open-ai-school.vercel.app](https://open-ai-school.vercel.app)** and start your first lesson — it takes 10 minutes!

## 🤝 Contributing

We welcome contributions from everyone! Here's how you can help:

- 🌍 **Translate** — Add your language ([see open issues](https://github.com/open-ai-school/ai-seeds/labels/good%20first%20issue))
- ✍️ **Write lessons** — Share your AI knowledge
- 💻 **Code** — Dark mode, new features, AI demos
- 📣 **Share** — Tell your friends, classmates, communities
- 💬 **Discuss** — Join our [Discussions](https://github.com/open-ai-school/ai-seeds/discussions)

Check out our [contribution guide](https://github.com/open-ai-school/ai-seeds/blob/main/CONTRIBUTING.md) to get started.

## 👨‍💻 Built By

**[Ramesh Reddy Adutla](https://github.com/rameshreddy-adutla)** — Staff Software Engineer with 14+ years of experience, passionate about making AI education accessible to everyone.

- 🔗 [LinkedIn](https://linkedin.com/in/rameshreddy-adutla)
- ☕ [Buy Me a Coffee](https://buymeacoffee.com/rameshreddyadutla)

---

<div align="center">

**⭐ Star our repos if you believe in free AI education for all**

</div>
