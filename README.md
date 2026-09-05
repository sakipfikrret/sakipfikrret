<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:09090b,35:18181b,70:312e81,100:06b6d4&height=240&section=header&text=Fikret%20%C3%87alk%C4%B1n&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Software%20Developer%20%7C%20AI%20Systems%20Enthusiast&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=21&duration=2800&pause=900&color=06B6D4&center=true&vCenter=true&width=850&lines=Software+Developer+%F0%9F%92%BB;AI+Systems+Enthusiast+%F0%9F%A7%A0;Building+Autonomous+AI+Systems+%F0%9F%A4%96;Full-Stack+%26+Backend+Developer+%F0%9F%8C%90;Security+%7C+Automation+%7C+Developer+Tools;Always+Learning.+Always+Building." alt="Typing SVG"/>

<br/><br/>

<a href="https://github.com/sakipfikrret">
<img src="https://img.shields.io/badge/GitHub-sakipfikrret-18181b?style=for-the-badge&logo=github"/>
</a>

<img src="https://komarev.com/ghpvc/?username=sakipfikrret&style=for-the-badge&color=06b6d4&label=PROFILE+VIEWS"/>

<img src="https://img.shields.io/github/followers/sakipfikrret?style=for-the-badge&logo=github&label=FOLLOWERS&color=312e81"/>

</div>

---

# 👋 Hi, I'm Fikret Çalkın

<p align="center">
<strong>Software Developer • AI Systems Enthusiast • Problem Solver</strong>
</p>

I'm an **Internet & Network Technologies graduate** interested in building software systems, AI-powered applications, automation tools, developer tools, and experimental AI architectures.

I enjoy taking an idea through:

<p align="center">

💡 <b>Concept</b>
&nbsp;→&nbsp;
🏗️ <b>Architecture</b>
&nbsp;→&nbsp;
💻 <b>Implementation</b>
&nbsp;→&nbsp;
🧪 <b>Testing</b>
&nbsp;→&nbsp;
🔍 <b>Iteration</b>
&nbsp;→&nbsp;
🚀 <b>Improvement</b>

</p>

---

# 🚀 Featured Project

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:09090b,50:312e81,100:06b6d4&height=110&text=OCTOREVIEW-AI&fontSize=42&fontColor=ffffff&animation=fadeIn" width="90%"/>

<br/><br/>

<a href="https://github.com/sakipfikrret/octoreview-ai">
<img src="https://img.shields.io/badge/VIEW%20PROJECT-18181b?style=for-the-badge&logo=github"/>
</a>

<a href="https://github.com/sakipfikrret/octoreview-ai">
<img src="https://img.shields.io/github/stars/sakipfikrret/octoreview-ai?style=for-the-badge&logo=github&label=STARS&color=06b6d4"/>
</a>

<a href="https://github.com/sakipfikrret/octoreview-ai">
<img src="https://img.shields.io/github/license/sakipfikrret/octoreview-ai?style=for-the-badge&label=LICENSE"/>
</a>

</div>

<br/>

### 🤖 Autonomous GitHub Pull Request Reviewer

**OctoReview-AI** is an engineering-focused AI code review platform and CLI agent designed to inspect GitHub Pull Requests with automated security, performance, architectural and code-health analysis.

Instead of simply generating a generic AI response, OctoReview-AI presents findings directly alongside the code diff through an interactive developer-focused interface.

---

## 🖥️ OctoReview-AI Dashboard

<div align="center">

<a href="https://github.com/sakipfikrret/octoreview-ai">

<img src="https://raw.githubusercontent.com/sakipfikrret/octoreview-ai/main/public/assets/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202026-09-06%20011428.png" alt="OctoReview-AI Dashboard" width="95%"/>

</a>

<br/>

<sub>Interactive OctoReview-AI review dashboard</sub>

</div>

---

## 🧠 What Makes It Different?

<div align="center">

<table>
<tr>
<td align="center" width="25%">

### 🔐
### Security

Security vulnerability detection

</td>

<td align="center" width="25%">

### 🧠
### AI Reasoning

LLM-assisted code analysis

</td>

<td align="center" width="25%">

### 🔎
### Diff Analysis

Inline code diagnostics

</td>

<td align="center" width="25%">

### 📊
### Code Health

Risk & complexity metrics

</td>
</tr>
</table>

</div>

---

# ⚡ Core Features

### 🔐 Security Analysis

Detects potential problems such as:

- Hardcoded secrets
- Security vulnerabilities
- Dangerous patterns
- Architectural risks
- Potential race conditions
- Memory-related problems

---

### 🧠 AI-Powered Code Review

The analysis engine evaluates code changes with an LLM-based reasoning layer.

The system focuses on:

```text
Security
   +
Performance
   +
Architecture
   +
Code Health
   ↓
Actionable Diagnostics
```

---

### 🔎 Interactive Diff Inspector

OctoReview-AI provides a GitHub-style diff interface with:

- Multi-file diff inspection
- Collapsible files
- Addition / deletion statistics
- Inline diagnostics
- Exact line references
- Suggested fixes
- One-click copy interactions

---

### 📊 Review Health Dashboard

The interface exposes multiple signals for each review:

```text
┌─────────────────────────────────────────┐
│                                         │
│       SECURITY RISK                     │
│       ─────────────                     │
│                                         │
│       CODE HEALTH                       │
│       ───────────                       │
│                                         │
│       COMPLEXITY IMPACT                 │
│       ─────────────────                 │
│                                         │
│       CI / CD STATUS                    │
│       ──────────────                    │
│                                         │
└─────────────────────────────────────────┘
```

---

### ⌨️ Keyboard-First Workflow

Designed with Linear / Vim-style navigation principles.

| Key | Action |
|:---:|---|
| `j` | Next review |
| `k` | Previous review |
| `Enter` | Open selected review |
| `Space` | Open selected review |

The goal is to make Pull Request triage faster without constantly reaching for the mouse.

---

# 🏗️ Architecture

```text
                    ┌──────────────────────┐
                    │   GitHub Pull Request │
                    │      / Raw Diff       │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Action Runner / CLI  │
                    │    / Web Interface   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Git Diff Parser &     │
                    │     Normalizer        │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ LLM Reasoning + AST   │
                    │      Evaluation       │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Structured Findings  │
                    │    & Health Metrics  │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ OctoReview Dashboard │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Developer Review /   │
                    │     One-Click Fix    │
                    └──────────────────────┘
```

---

# 🧰 Technology Behind OctoReview

<div align="center">

<img src="https://skillicons.dev/icons?i=typescript,react,vite,tailwind,nodejs,python,github&theme=dark" alt="Tech Stack"/>

<br/><br/>

<img src="https://img.shields.io/badge/TypeScript-5.8-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Vite-6-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>

<br/>

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-Automation-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/LLM-AI%20Reasoning-7C3AED?style=for-the-badge"/>

</div>

---

# 🧩 Project Components

```text
octoreview-ai/
│
├── 🐍 octoreview/
│   ├── analyzer.py
│   ├── github.py
│   ├── config.py
│   ├── exceptions.py
│   └── cli.py
│
├── ⚛️ src/
│   ├── components/
│   │   ├── dashboard/
│   │   ├── diff-viewer/
│   │   └── modals/
│   │
│   ├── hooks/
│   ├── types/
│   ├── lib/
│   └── App.tsx
│
├── 🖼️ public/
│   └── assets/
│
├── 📦 package.json
├── 🐍 requirements.txt
└── 📄 README.md
```

---

# 🚀 Three Ways To Use It

### 01 — GitHub Action

Automatically analyze Pull Requests inside CI/CD workflows.

```yaml
on:
  pull_request:
    types: [opened, synchronize, reopened]
```

---

### 02 — Web Dashboard

Analyze a GitHub Pull Request or paste a raw Git diff directly into the interactive dashboard.

```text
GitHub PR URL
      │
      ▼
Analyze Diff
      │
      ▼
AI Review
      │
      ▼
Security + Performance + Architecture
      │
      ▼
Interactive Findings
```

---

### 03 — CLI

Run code analysis directly from the terminal.

```bash
git diff main | python -m octoreview.cli --stdin
```

Or inspect a GitHub PR:

```bash
python -m octoreview.cli --repo "owner/repository" --pr 123
```

---

# 🔬 Other Areas I'm Exploring

## 🤖 Artificial Intelligence

```text
Local LLMs
   │
   ├── AI Agents
   ├── Knowledge Graphs
   ├── Graph-RAG
   ├── Memory Systems
   ├── Expert Architectures
   └── Neuro-Symbolic AI
```

## 💻 Software Engineering

```text
Backend Architecture
   │
   ├── API Design
   ├── Full-Stack Development
   ├── Testing
   ├── Automation
   └── System Reliability
```

## 🛠️ Developer Tools

```text
Developer Productivity
   │
   ├── Code Analysis
   ├── Testing Tools
   ├── Automation
   ├── AI-assisted Development
   └── Experimental Tooling
```

---

# 🧠 Development Philosophy

I don't just want software to **work**.

I want to understand:

```text
WHY does it work?
        ↓
WHERE can it fail?
        ↓
HOW can it be improved?
        ↓
CAN the architecture be better?
        ↓
CAN the idea become something bigger?
```

My usual development loop:

<div align="center">

### 💡 IDEA
### ↓
### 🧪 PROTOTYPE
### ↓
### 🔍 TEST
### ↓
### ⚠️ FIND WEAKNESSES
### ↓
### 🔧 IMPROVE
### ↓
### ♻️ REFACTOR
### ↓
### 🚀 REPEAT

</div>

---

# 📊 GitHub Statistics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=sakipfikrret&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&rank_icon=github"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sakipfikrret&layout=compact&theme=tokyonight&hide_border=true"/>

</div>

<br/>

<div align="center">

<img src="https://streak-stats.demolab.com?user=sakipfikrret&theme=tokyonight&hide_border=true" width="70%"/>

</div>

---

# 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=sakipfikrret&theme=tokyonight&no-frame=true&no-bg=true&margin-w=10&row=1&column=6" width="95%"/>

</div>

---

# 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sakipfikrret&theme=tokyo-night&hide_border=true&area=true" width="95%"/>

</div>

---

# 📌 Current Focus

<div align="center">

| 🧠 Local AI | 🤖 Autonomous Agents | 🕸️ Knowledge Graphs |
|:---:|:---:|:---:|
| Local-first architectures | Intelligent automation | Graph-RAG |

| 🔐 Code Security | ⚙️ Developer Tools | 🧪 Experimental AI |
|:---:|:---:|:---:|
| AI-assisted analysis | Developer productivity | New architectures |

</div>

---

# 📫 Connect

<div align="center">

<a href="https://github.com/sakipfikrret">
<img src="https://img.shields.io/badge/GitHub-sakipfikrret-18181b?style=for-the-badge&logo=github"/>
</a>

<a href="https://github.com/sakipfikrret/octoreview-ai">
<img src="https://img.shields.io/badge/Featured%20Project-OctoReview--AI-06b6d4?style=for-the-badge&logo=github"/>
</a>

</div>

---

<div align="center">

### ⚡ "I like building things that shouldn't be easy to build."

<br/>

Whether it's an AI architecture, a developer tool,
a full-stack application, or an experimental idea —

**I enjoy turning concepts into working software.**

<br/>

<strong>Always learning. Always experimenting. Always building.</strong>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:312e81,100:09090b&height=130&section=footer" width="100%"/>

</div>
