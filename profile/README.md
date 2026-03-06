<div align="center">

# 🎓 AI Educademy

### Free, open-source, multilingual AI education for everyone

[![Website](https://img.shields.io/badge/Website-aieducademy.vercel.app-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://aieducademy.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](https://github.com/ai-educademy/ai-platform/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/ai-educademy?style=for-the-badge&color=ff9f0a)](https://github.com/ai-educademy)

---

**Learn AI from zero — no coding, no maths, no jargon.**

🌍 Available in **English** · **Français** · **Nederlands** · **हिन्दी** · **తెలుగు** · *more coming soon!*

</div>

## 🌱 Our Mission

AI education should be **free**, **accessible**, and **available in your language**. Too many learners — especially in the Global South — are left behind because quality AI resources are in English, behind paywalls, or assume prior technical knowledge.

AI Educademy starts from the very basics and builds understanding step by step, using everyday language and real-world analogies.

## 🗺️ Learning Tracks

### Understanding AI
```
🌱 AI Seeds       →  Absolute beginners, zero experience
🌿 AI Sprouts     →  Foundations & core concepts
🌳 AI Branches    →  Applied AI & real-world use cases
🏕️ AI Canopy      →  Advanced topics & specialisation
🌲 AI Forest      →  Expert-level, research & contribution
```

### Code & Algorithms
```
✏️ AI Sketch       →  Data structures & problem solving basics
🪨 AI Chisel       →  Intermediate algorithms & patterns
🔨 AI Craft        →  System design & architecture
💎 AI Polish       →  Optimisation & advanced techniques
🏆 AI Masterpiece  →  Interview-ready mastery
```

## 📦 Repository Map

| Repo | Role | Description |
|------|------|-------------|
| [`ai-platform`](https://github.com/ai-educademy/ai-platform) | 🌐 App Shell | Next.js 16, React 19, i18n, auth, routing — the deployed site |
| [`ai-courses`](https://github.com/ai-educademy/ai-courses) | 📚 Content | All lesson content (MDX) across both tracks |
| [`ai-ui-lib`](https://github.com/ai-educademy/ai-ui-lib) | 🎨 Design System | Shared React components — Button, Card, ThemeToggle, animations |
| [`gitsage`](https://github.com/ai-educademy/gitsage) | 🧙 Dev Tool | RAG-powered GitHub org bot — Java 21, LangChain4j, pgvector |

### Architecture

```
┌──────────────────────────────────────────────────────┐
│                    ai-platform                        │
│           Next.js 16 app shell (Vercel)               │
│      routing · auth · i18n · program registry         │
├─────────────────┬────────────────────────────────────┤
│   ai-ui-lib     │          ai-courses                 │
│  (npm package)  │  ┌───────────────────────────────┐  │
│                 │  │  Understanding AI              │  │
│  Button · Card  │  │  🌱 Seeds → 🌿 Sprouts →      │  │
│  Badge · Theme  │  │  🌳 Branches → 🏕️ Canopy →    │  │
│  Animations     │  │  🌲 Forest                     │  │
│                 │  ├───────────────────────────────┤  │
│                 │  │  Code & Algorithms             │  │
│                 │  │  ✏️ Sketch → 🪨 Chisel →       │  │
│                 │  │  🔨 Craft → 💎 Polish →        │  │
│                 │  │  🏆 Masterpiece                │  │
│                 │  └───────────────────────────────┘  │
├─────────────────┴────────────────────────────────────┤
│          🧙 gitsage — RAG-powered org bot             │
│        Java 21 · LangChain4j · Micronaut · pgvector   │
└──────────────────────────────────────────────────────┘
```

## 🚀 Get Started

Visit **[aieducademy.vercel.app](https://aieducademy.vercel.app)** and start your first lesson — it takes 10 minutes!

## 🤝 Contributing

We welcome contributions from everyone:

- 🌍 **Translate** — Add your language to the content repo
- ✍️ **Write lessons** — Share your AI or coding knowledge
- 🧩 **Build components** — Contribute to the UI library
- 💻 **Code** — Features, fixes, new programs
- 📣 **Share** — Tell your friends, classmates, communities

## 👨‍💻 Built By

[**@rameshreddy-adutla**](https://github.com/rameshreddy-adutla) — Tech Lead, 14 years experience · London

---

<div align="center">

**⭐ Star our repos if you believe in free AI education for all**

</div>
