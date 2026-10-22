<h1 align="center">Hi, I'm Cristopher 👋</h1>

<p align="center">
I build the software I live with: <b>AI agents</b>, <b>macOS tools</b> and an <b>always-on room display</b>.
</p>

<p align="center">
<img src="assets/ton-618.gif" width="100%" alt="Pixel-art animation of TON 618, an ultramassive black hole" />
<br />
<sub>TON 618 — an ultramassive black hole, ~66 billion solar masses</sub>
</p>

<p align="center">
<sub><b>NOW</b> &nbsp;·&nbsp; bringing Personal Hub up on its Windows host &nbsp;·&nbsp; shipping Grocery Tracker on iOS 26</sub>
</p>

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-24292F?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-24292F?style=for-the-badge&logo=javascript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-24292F?style=for-the-badge&logo=swift&logoColor=white)
![Objective-C++](https://img.shields.io/badge/Objective--C++-24292F?style=for-the-badge&logo=apple&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-24292F?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Frameworks & Runtime**

![React](https://img.shields.io/badge/React-24292F?style=for-the-badge&logo=react&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-24292F?style=for-the-badge&logo=electron&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-24292F?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-24292F?style=for-the-badge&logo=node.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-24292F?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-24292F?style=for-the-badge&logo=tailwindcss&logoColor=white)

**AI & Data**

![Claude API](https://img.shields.io/badge/Claude_API-24292F?style=for-the-badge&logo=claude&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-24292F?style=for-the-badge&logo=ollama&logoColor=white)
![LM Studio](https://img.shields.io/badge/LM_Studio-24292F?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-24292F?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-24292F?style=for-the-badge&logo=sqlite&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-24292F?style=for-the-badge)

**Automation & Integrations**

![Playwright](https://img.shields.io/badge/Playwright-24292F?style=for-the-badge)
![Google Calendar](https://img.shields.io/badge/Google_Calendar-24292F?style=for-the-badge&logo=googlecalendar&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail_API-24292F?style=for-the-badge&logo=gmail&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify_API-24292F?style=for-the-badge&logo=spotify&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-24292F?style=for-the-badge&logo=githubactions&logoColor=white)

## Projects

### Personal Hub
A wall display running 24/7: alarms, routines, automations and a local tool-calling agent. A deterministic intent router handles everyday commands, so the small model on a GTX 1050 is only the fallback.
<br /><sub>ELECTRON · FASTAPI · SQLITE · CHROMADB · LM STUDIO &nbsp;🔒</sub>

### Jupiter
A personal AI assistant that routes across Claude, GPT and Gemini with 33 tools. Its "Doorman" triages Gmail, Instagram and TikTok messages and drafts replies for me to approve.
<br /><sub>FASTAPI · REACT · LITELLM · CHROMADB · PLAYWRIGHT &nbsp;🔒</sub>

### Personal Widget
A macOS widget that lives among the Finder icons and still takes clicks, made possible by a small Objective-C++ addon that sets the native window level.
<br /><sub>ELECTRON · REACT · OBJECTIVE-C++ &nbsp;🔒</sub>

### Grocery Tracker
An iPhone app that reads receipts on the device with Apple Intelligence and flags what has probably run out. No account, no server.
<br /><sub>SWIFT · iOS 26 · APPLE INTELLIGENCE &nbsp;🔒</sub>

<details>
<summary><b>More projects</b></summary>
<br />

| | |
|---|---|
| [**MyTime-Agent**](https://github.com/Farflan/MyTime-Agent) | Syncs my work schedule and answers questions about it with Claude |
| [**AI-Fitness-Nutrition-Agent**](https://github.com/Farflan/AI-Fitness-Nutrition-Agent) | Macro tracker with an AI nutrition coach |
| **Mac File Organizer** 🔒 | Previews every move first, with a one-command undo and an MCP server |
| **Obsidian Note Taker** 🔒 | Auto-tags and links notes with a local Ollama model |
| **Family Dashboard** 🔒 | Kitchen screensaver with live weather and a sun-and-moon horizon |

</details>

## How it connects

<sub>Each project borrows from the one before it.</sub>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'lineColor':'#8B949E','fontFamily':'ui-sans-serif, system-ui, sans-serif'}}}%%
flowchart LR
  J("Jupiter") --> H("Personal Hub")
  D("Linux Dashboard") --> W("Personal Widget") --> H
  G1("Grocery PWA") --> G2("Grocery iOS")
  classDef node fill:#24292F,stroke:#57606A,color:#F0F6FC
  class J,H,D,W,G1,G2 node
```

---

<p align="center"><sub><i>If it doesn't survive daily use, it doesn't ship.</i> &nbsp;·&nbsp; 🔒 private repo</sub></p>
