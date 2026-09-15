# 🎨 AI PDD Generator

Generate comprehensive **Product Design Documents** through warm, conversational AI interviews.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.2.0-blue.svg)]()

> Inspired by advanced prompting techniques from Claude Fable 5, Cursor, Lovable, and Devin.

## ✨ Features

- 🗣️ **Conversational Interview** — AI asks questions one by one, like talking to a friend
- 🇮🇩 **Indonesian & English** — Natural bilingual support
- 🎯 **Fable 5 Style** — Warm, friendly, no AI-isms
- 📝 **Non-Technical Summary** — Simple explanation at the end
- 🔧 **Multi-Tool** — Works with Claude Code, Codex, OpenCode, Hermes Agent

## 📦 Installation

### Claude Code
```bash
git clone https://github.com/Vann4799/ai-pdd-generator.git ~/.claude/ai-pdd-generator
```

### Codex
```bash
git clone https://github.com/Vann4799/ai-pdd-generator.git ~/.codex/ai-pdd-generator
```

### OpenCode
```bash
git clone https://github.com/Vann4799/ai-pdd-generator.git ~/.opencode/skills/ai-pdd-generator
```

### Hermes Agent
```bash
hermes skills install Vann4799/ai-pdd-generator
```

## 🎯 Usage

Simply say:

```
"Buat PDD untuk aplikasi kasir toko"
```

## 📋 Interview Questions

| # | Question (ID) | Question (EN) |
|---|--------------|---------------|
| 1 | Apa nama aplikasinya? | What's the project name? |
| 2 | Jenis aplikasinya apa? | What type of project? |
| 3 | Tampilannya mau kayak gimana? | What's the design style? |
| 4 | Siapa yang bakal pakai? | Who are the target users? |
| 5 | Gimana cara orang pakai? | What are the user flows? |
| 6 | Halaman apa aja yang ada? | What are the key screens? |
| 7 | Ada aturan khusus untuk tampilan? | Any design constraints? |
| 8 | Mau Bahasa Indonesia atau English? | Language preference? |


## 📄 Output Structure

1. Design Goals
2. Target Users (with personas)
3. User Flows (with ASCII diagrams)
4. Key Screens & Features
5. Design Specifications (colors, typography, spacing)
6. Design Constraints
7. Task List
8. Non-Technical Summary

## 🤝 Contributing

PRs welcome!

## 📄 License

MIT License

---

Made with ❤️ by [Vann4799](https://github.com/Vann4799)
