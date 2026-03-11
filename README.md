# 🪲 BUGRAIDER — Deep Code Audit & Intelligent QA Agent

> **A powerful system prompt that turns any AI agent into a world-class code auditor.**
> Drop it into Claude, ChatGPT, Gemini, Cursor, or Windsurf — and watch it scan your entire project like a senior engineer.

---

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-nRn--Open-green)
![Works With](https://img.shields.io/badge/works%20with-Claude%20%7C%20GPT--4%20%7C%20Gemini%20%7C%20Cursor%20%7C%20Windsurf-purple)
![Made by](https://img.shields.io/badge/made%20by-nRn%20World-orange)

---

## ⚠️ IMPORTANT DISCLAIMER — READ BEFORE USE

> **BY DOWNLOADING, COPYING, OR USING BUGRAIDER IN ANY WAY, YOU FULLY ACCEPT THE TERMS BELOW.
> IF YOU DO NOT AGREE, DO NOT USE THIS PROMPT.**

**BUGRAIDER is a text-based prompt. It is NOT software, NOT an application, and NOT a service.**
It instructs an AI language model (such as Claude, GPT-4, or Gemini) to analyze code.
nRn World has no control over how any AI model interprets or acts upon this prompt.

**nRn World, its creator, and any contributors are NOT responsible or liable for:**

- Any **damage, deletion, corruption, or loss of code or data** resulting from using this prompt
- Any **broken functionality, crashes, or bugs introduced** by AI-suggested fixes applied by the user
- Any **security vulnerabilities missed** by the AI agent — BUGRAIDER does not guarantee complete coverage
- Any **financial loss, business interruption, or lost revenue** caused directly or indirectly by this prompt
- Any **incorrect, incomplete, or misleading analysis** produced by an AI model using this prompt
- Any **consequences of applying AI-suggested code changes** without proper review and testing
- Any **third-party claims, lawsuits, or damages** arising from code modified using this prompt
- Any **data breaches or security incidents** that occur in a project that was audited using this prompt

**YOU are solely and fully responsible for:**

- Reviewing every AI suggestion before applying it
- Backing up your entire project before running any audit or applying any fix
- Testing your project thoroughly after any changes
- Using professional human code review for production-critical or security-critical systems
- Any and all decisions made based on the output of this prompt

**BUGRAIDER is provided "AS IS", without warranty of any kind — express, implied, or statutory — including but not limited to warranties of merchantability, fitness for a particular purpose, accuracy, completeness, or non-infringement.**

> **TL;DR — Use at your own risk. Always back up your code first. We are not liable for anything that goes wrong. You are responsible for every change made to your codebase.**

---

## 🔍 What is BUGRAIDER?

BUGRAIDER is a deeply detailed **system prompt** that activates any AI agent as a professional-grade Software Quality Assurance and Security Auditing Agent.

Inspired by tools like **TestSprite**, **SonarQube**, and **Snyk** — but works entirely through conversation with your AI agent of choice.

When activated, BUGRAIDER will:

- 📁 **Map your entire project** — every folder, file, asset, and configuration
- 🔬 **Deep scan all your code** — C#, Python, JavaScript, TypeScript, HTML, CSS, SQL, YAML, and more
- 🔐 **Hunt for security vulnerabilities** — exposed API keys, missing auth, injection risks
- 🐛 **Find bugs and logic errors** — null crashes, infinite loops, race conditions
- ⚡ **Detect performance issues** — memory leaks, per-frame GetComponent, N+1 queries
- 🧹 **Flag dead code** — unused functions, orphaned assets, commented-out blocks
- 📊 **Generate a full structured report** with severity levels (Critical / High / Medium / Low)
- 🤝 **Ask you how to proceed** — fix everything, step by step, or just export the report

**It never touches your code without your explicit approval.**

---

## ⚡ Quick Start

### Option 1 — Paste as System Prompt
Copy the entire contents of `BUGRAIDER_PROMPT.md` and paste it as the **system prompt** in your AI tool.

### Option 2 — Paste as First Message
Copy the entire contents of `BUGRAIDER_PROMPT.md` and paste it as your **first message** in a new conversation.

Then share your code, paste your files, or give the agent access to your repository.

BUGRAIDER will respond with:

```
🪲 BUGRAIDER ACTIVATED
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Deep Code Audit Agent — Online
Mode: Full Project Scan
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Starting Phase 1: Project Mapping...
```

---

## 🤖 Compatible With

| AI Agent | Status |
|---|---|
| Claude (Anthropic) | ✅ Fully Compatible |
| ChatGPT / GPT-4o (OpenAI) | ✅ Fully Compatible |
| Gemini (Google) | ✅ Fully Compatible |
| Cursor | ✅ Fully Compatible |
| Windsurf | ✅ Fully Compatible |
| GitHub Copilot Chat | ✅ Fully Compatible |
| Any other LLM-based agent | ✅ Should work |

---

## 🗂️ What BUGRAIDER Scans

### Languages & Frameworks
- **C# / Unity** — MonoBehaviours, coroutines, shaders, prefabs, scene files
- **JavaScript / TypeScript** — React, Vue, Angular, Next.js, Node.js
- **Python** — Django, FastAPI, Flask, scripts
- **HTML / CSS** — Accessibility, SEO, broken links, media queries
- **SQL** — Injection vulnerabilities, missing indexes, N+1 queries
- **Config files** — YAML, JSON, TOML, Dockerfile, CI/CD pipelines

### Issue Categories
| Severity | Examples |
|---|---|
| 🔴 Critical | Exposed API keys, crash bugs, missing authentication |
| 🟠 High | Memory leaks, per-frame GetComponent, unhandled errors |
| 🟡 Medium | Dead code, magic numbers, duplicate logic |
| 🔵 Low | Debug logs, style inconsistencies, trailing whitespace |
| ⚪ Info | Missing tests, outdated dependencies, docs gaps |

---

## 📋 Example Output

After scanning your project, BUGRAIDER delivers a structured report like this:

```
BUGRAIDER AUDIT REPORT
Project         : MyAwesomeGame
Total Issues    : 18
──────────────────────────────────────────
🔴 Critical Issues    : 2
🟠 High Issues        : 3
🟡 Medium Issues      : 6
🔵 Low Issues         : 7
──────────────────────────────────────────
Overall Health Score  : 64/100
Security Score        : 71/100
Code Quality Score    : 58/100
Performance Score     : 70/100
```

Followed by a full table of every issue with file path, line number, severity, and description.

Then BUGRAIDER asks:

```
How would you like to proceed?

Option A — Fix Everything Automatically
Option B — Step by Step (Recommended)
Option C — Fix Only Critical & High Issues
Option D — Show Me One Specific Issue
Option E — Export the Report Only

What is your choice? (A / B / C / D / E)
```

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `BUGRAIDER_PROMPT.md` | The full BUGRAIDER system prompt — paste this into your AI agent |
| `BUGRAIDER_PROMPT.pdf` | PDF version for reading, sharing, and reference |
| `README.md` | This file |
| `LICENSE` | nRn Open Attribution License |

---

## 📜 License

This project is licensed under the **nRn Open Attribution License**.

- ✅ Free to use personally
- ✅ Free to modify and improve
- ✅ Free to share and distribute
- ✅ Free to use in commercial projects
- ⚠️ **If you earn money using this prompt (directly or as part of a product/tool/service), you must include the following attribution somewhere visible in your project, product, or codebase:**

```
© 2026 nRn World — BUGRAIDER Prompt. All rights reserved.
```

See the full `LICENSE` file for details.

---

## 🙌 Contributing

Found a way to improve BUGRAIDER? Open a Pull Request or Issue!

Suggestions are welcome for:
- New language-specific scan rules (Rust, Go, Swift, Kotlin, etc.)
- New security checks
- Better formatting or structure
- Translation to other languages

---

👨‍💻 **Author**  
Created 2026 by © nRn World

📧 bynrnworld@gmail.com

## 🙏 Support

If you like this project, consider:

* ⭐ Star the project on GitHub  
* ☕ [Buy me a coffee](https://buymeacoffee.com/nrnworld)  
* 📢 Share with your friends  
* ☕ Buying me a coffee  
* 📢 Sharing with your friends
