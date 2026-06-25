# Think-Zone 🧠

**Local-first AI infrastructure — own your stack, own your data, own your AI.**

[![cognitive-mcp](https://img.shields.io/badge/cognitive--mcp-v0.1.0-blue)](https://github.com/think-zone/cognitive-mcp)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/think-zone/cognitive-mcp/blob/main/LICENSE)
[![Built with MCP](https://img.shields.io/badge/protocol-MCP-purple)](https://modelcontextprotocol.io)

---

## What We Build

Think-Zone is an open-source ecosystem for running powerful AI workflows entirely on your own hardware — no cloud lock-in, no subscriptions, no surveillance.

We build the infrastructure layer between local LLMs and real automation: MCP servers, autonomous agents, and full-stack applications that run at the edge of a single machine.

---

## Projects

| Project | Status | What It Does |
|---------|--------|--------------|
| [**creator-os**](https://github.com/think-zone/creator-os) | 🔨 Active | Full-stack monorepo powering [api.meshtool.ai](https://api.meshtool.ai), [app.meshtool.ai](https://app.meshtool.ai), and [disco-bass.com](https://disco-bass.com) — Hono APIs + Next.js apps + shared SDKs, deployed on Railway & Vercel |
| [**cognitive-mcp**](https://github.com/think-zone/cognitive-mcp) | 🚀 v0.1.0 | MCP server for persistent agent memory — four tools, one SQLite file, zero cloud dependencies |

---

## Live Products

| Product | URL | Description |
|---------|-----|-------------|
| MeshTool API | [api.meshtool.ai](https://api.meshtool.ai) | Agentic API + MCP endpoint for skill/agent execution |
| MeshTool App | [app.meshtool.ai](https://app.meshtool.ai) | Browse, acquire, and run AI skills & agents |
| DiscoSlop | [disco-bass.com](https://disco-bass.com) | AI DJ web app — real-time music generation |

---

## Tech Stack

- **Runtime:** WSL2 + Ubuntu, Docker, Ollama
- - **Languages:** TypeScript, Python, Bash
  - - **AI Layer:** Local LLMs (Llama, Mistral, Qwen) + Claude via MCP
    - - **Automation:** n8n, GitHub Actions, custom agent workflows
      - - **Protocol:** [Model Context Protocol (MCP)](https://modelcontextprotocol.io) for all agent tooling
        - - **Infra:** Railway, Vercel, Neon (Postgres), Redis
         
          - ---

          ## Philosophy

          > Most AI tools rent you access to someone else's compute. We think that's backwards.
          >
          > Think-Zone is built on the belief that the best AI infrastructure is the kind you run yourself — fast, private, and fully under your control. Every tool we ship is local-first by default, open-source by design, and production-grade by necessity.
          >
          > ---
          >
          > ## Get Involved
          >
          > - ⭐ **Star [cognitive-mcp](https://github.com/think-zone/cognitive-mcp)** — follow development of our flagship MCP server
          > - - 🐛 **Open issues** — we build in public and feedback from builders makes the tools better
          >   - - 🤝 **Collaborate or invest** — reach out via GitHub or open a Discussion
          >    
          >     - ---
          >
          > *Built with obsession by a solo founder. Designed for the next generation of local-first AI.*
