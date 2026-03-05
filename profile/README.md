<div align="center">

# 🎓 Open AI School

### Free, open-source, multilingual AI education for everyone

[![Website](https://img.shields.io/badge/Website-open--ai--school.vercel.app-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://open-ai-school.vercel.app)
[![npm](https://img.shields.io/npm/v/@open-ai-school/ai-ui-library?style=for-the-badge&color=f59e0b&label=UI%20Library)](https://www.npmjs.com/package/@open-ai-school/ai-ui-library)
[![License](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](https://github.com/open-ai-school/ai-platform/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/open-ai-school?style=for-the-badge&color=ff9f0a)](https://github.com/open-ai-school)

---

**Learn AI from zero — no coding, no maths, no jargon.**

🌍 Available in **English** · **Français** · **Nederlands** · **हिन्दी** · **తెలుగు** · *more coming soon!*

</div>

## 🌱 Our Mission

AI education should be **free**, **accessible**, and **available in your language**. Too many learners — especially in the Global South — are left behind because quality AI resources are in English, behind paywalls, or assume prior technical knowledge.

Open AI School starts from the very basics and builds understanding step by step, using everyday language and real-world analogies.

## 🗺️ Learning Path

```
🌱 AI Seeds       →  Absolute beginners, zero experience
🌿 AI Sprouts     →  Foundations & core concepts (coming soon)
🌳 AI Branches    →  Applied AI & real-world use cases (coming soon)
🏕️ AI Canopy      →  Advanced topics & specialisation (coming soon)
🌲 AI Forest      →  Expert-level, research & contribution (coming soon)
```

## 📦 Repository Map

| Repo | Role | Description |
|------|------|-------------|
| [`ai-platform`](https://github.com/open-ai-school/ai-platform) | 🌐 App Shell | Next.js 16, React 19, i18n, auth, routing — the deployed site |
| [`ai-ui-library`](https://github.com/open-ai-school/ai-ui-library) | 🎨 Design System | Shared components on [npm](https://www.npmjs.com/package/@open-ai-school/ai-ui-library) — Button, Card, ThemeToggle, animations |
| [`ai-seeds`](https://github.com/open-ai-school/ai-seeds) | 🌱 Level 1 Content | MDX lessons for absolute beginners |
| [`gitsage`](https://github.com/open-ai-school/gitsage) | 🧙 Dev Tool | RAG-powered GitHub org bot — Java 21, LangChain4j, pgvector |
| [`spring-boot-mcp-starter`](https://github.com/open-ai-school/spring-boot-mcp-starter) | 🔌 Dev Tool | Spring Boot starter for Model Context Protocol |

### Architecture

```
┌─────────────────────────────────────────────────┐
│                  ai-platform                     │
│         Next.js app shell (deployed)             │
│    routing · auth · i18n · program registry      │
├────────────────────┬────────────────────────────┤
│   ai-ui-library    │      Content Repos          │
│  (npm package)     │  ┌──────────────────────┐   │
│                    │  │ 🌱 ai-seeds          │   │
│  Button · Card     │  │ 🌿 ai-sprouts       │   │
│  Badge · Theme     │  │ 🌳 ai-branches      │   │
│  ScrollReveal      │  │ 🏕️ ai-canopy        │   │
│  Animations        │  │ 🌲 ai-forest        │   │
│                    │  └──────────────────────┘   │
└────────────────────┴────────────────────────────┘
```

## 🚀 Get Started

Visit **[open-ai-school.vercel.app](https://open-ai-school.vercel.app)** and start your first lesson — it takes 10 minutes!

## 🤝 Contributing

We welcome contributions from everyone:

- 🌍 **Translate** — Add your language to any content repo
- ✍️ **Write lessons** — Share your AI knowledge
- 🧩 **Build components** — Contribute to the UI library
- 💻 **Code** — Features, fixes, new programs
- 📣 **Share** — Tell your friends, classmates, communities

## 👨‍💻 Built By

[**@rameshreddy-adutla**](https://github.com/rameshreddy-adutla) — Tech Lead, 14 years experience · London

---

<div align="center">

**⭐ Star our repos if you believe in free AI education for all**

</div>
