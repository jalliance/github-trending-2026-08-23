# GitHub Trending Repositories — 2026-08-23 (Daily)

**Source**: Official [github.com/trending](https://github.com/trending) (today / daily ranking by stars gained in the last ~24h).  
**Snapshot time**: ~11:00 BST, Sunday 23 August 2026.  
**Note**: Rankings and star counts change rapidly. AI agent tooling currently dominates the top of the list.

This report is a permanent, revisitable record so you can review, star, fork, or dig into any of these projects at a time of your choosing.

## Quick Table (Top 12)

| Rank | Repository | Language | Approx. Stars (total / today) | Short Description |
|------|------------|----------|-------------------------------|-------------------|
| 1 | [openai/codex](https://github.com/openai/codex) | Rust | 114.5k / +1.5k | Lightweight coding agent that runs in your terminal |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | Shell | 233k / +2.7k | Skills for Real Engineers. Straight from my .agents directory. |
| 3 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | JavaScript | 242k / +411 | The agent harness performance optimization system (skills, memory, security, research-first) for Claude Code, Codex, Cursor & beyond |
| 4 | [obra/superpowers](https://github.com/obra/superpowers) | Shell | 276k / +592 | An agentic skills framework & software development methodology that works |
| 5 | [Wei-Shaw/sub2api](https://github.com/Wei-Shaw/sub2api) | Go | 39k / +278 | One-stop open-source relay/gateway for Claude / OpenAI / Gemini / Grok subscriptions; cost-sharing & unified access |
| 6 | [makeplane/plane](https://github.com/makeplane/plane) | TypeScript | 57k / +263 | Open-source Jira / Linear / Monday / ClickUp alternative for tasks, sprints, docs, triage |
| 7 | [n8n-io/n8n](https://github.com/n8n-io/n8n) | TypeScript | 202k / +149 | Fair-code workflow automation platform with native AI capabilities, visual + code, 400–1500+ integrations |
| 8 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | Python | 143k / +127 | Agentic coding tool that lives in your terminal, understands your codebase, handles git & routine tasks via natural language |
| 9 | [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) | Rust | 14.3k / +959 | Native, local-first alternative to Logitech Options+ — remap buttons, DPI, SmartShift over HID++. No account, no telemetry |
| 10 | [modular/modular](https://github.com/modular/modular) | Mojo | 29k / +395 | The Modular Platform (includes MAX inference framework & Mojo language) |
| 11 | [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev) | HTML | 134k / +829 | Curated list of SaaS/PaaS/IaaS offerings with free tiers useful to devops & infradev |
| 12 | [PostHog/posthog](https://github.com/PostHog/posthog) | Python | 39k / +286 | Open-source product analytics, session replay, feature flags, experiments, error tracking — self-driving product platform |

(Additional visible: multica-ai/andrej-karpathy-skills, mahlernim/google-timeline-visualizer, cursor/plugins, Tencent/AI-Infra-Guard, microsoft/TypeScript, etc.)

---

## Detailed Explanations

### 1. openai/codex
**What it does**: OpenAI’s lightweight, local-first coding agent that runs directly in your terminal (also has IDE integrations and a desktop app). It can use a ChatGPT subscription (Plus/Pro/Business/etc.) or an API key. Written primarily in Rust for speed and low overhead.

**Good for**: Developers who want a fast, terminal-native AI coding companion that stays local, integrates with existing workflows (VS Code, Cursor, etc.), and can execute routine coding, explanation, and git tasks without leaving the CLI. Ideal if you already pay for ChatGPT and want the agent experience without heavy frameworks.

**How to try**: `curl -fsSL https://chatgpt.com/codex/install.sh | sh` (or npm / Homebrew / binaries). Then run `codex`.

### 2. mattpocock/skills
**What it does**: A carefully crafted collection of small, composable “skills” (slash-commands / agent plugins) drawn from real engineering practice. Skills cover alignment (“grill-me”), domain modeling, TDD, structured debugging, architecture improvement, ticket breakdown, dual-axis code review, merge conflict resolution, etc. Designed for agents such as Claude Code and Codex.

**Good for**: Anyone using AI coding agents who is tired of “vibe coding” and wants the agent forced into disciplined engineering habits (test-first, clear specs, architecture awareness, proper reviews). Excellent for raising the quality floor of AI-assisted development.

**How to try**: `npx skills@latest add mattpocock/skills` or Claude plugin install. Then run `/setup-matt-pocock-skills` and start with `/grill-with-docs`.

### 3. affaan-m/ECC
**What it does**: A full “agent harness / operating system” for coding agents. Ships dozens of specialized agents, hundreds of skills, rules engines, memory vault (persistent cross-session context), security scanner (AgentShield), hooks, and installers for Claude Code, Codex, Cursor, OpenCode and many others. Enforces plan → test → implement → review → verify → remember → improve loops.

**Good for**: Teams or individuals who want production-grade, structured, memory-aware, security-conscious AI coding workflows that work across multiple agent tools. Turns agents from one-shot generators into reliable engineering systems.

**How to try**: Plugin install for Claude/Codex or `./install.sh --target <harness>`.

### 4. obra/superpowers
**What it does**: A complete agentic software-development methodology packaged as composable skills. Covers brainstorming with approval gates, strict TDD (red-green-refactor), subagent-driven development, systematic 4-phase debugging, git worktrees, mandatory code review, plan execution with verification steps, etc. Supports many agent harnesses.

**Good for**: Developers and teams who want AI agents to follow a proven, disciplined process rather than free-form generation. Especially useful when you need auditability, test evidence, and consistent quality from agent-written code.

**How to try**: Agent-specific plugin install (Claude, Devin, Pi, etc.). Skills activate automatically once installed.

### 5. Wei-Shaw/sub2api
**What it does**: Open-source API gateway / relay that lets you pool and share paid subscriptions (Claude, OpenAI, Gemini, Grok, etc.). Handles multi-account management, key distribution, precise token billing, load balancing, sticky sessions, rate limits, payment integrations, and an admin dashboard. Native-tool compatible.

**Good for**: Individuals or teams who want to share expensive AI subscriptions fairly, centralize API access, or run a private “AI API service” with cost tracking. Reduces per-user cost via carpooling while keeping native tool compatibility.

**How to try**: Docker Compose or install script on a Linux server with Postgres + Redis. Access the setup wizard at port 8080.

### 6. makeplane/plane
**What it does**: Modern, open-source project-management platform (issues, cycles/sprints with burndown, modules, pages/docs, custom views, real-time analytics). Built as a self-hostable alternative to Jira, Linear, Monday.com, ClickUp.

**Good for**: Teams that want a clean, fast, fully-featured agile tool without vendor lock-in or high SaaS costs. Excellent for product/engineering teams that value self-hosting or the free Plane Cloud tier.

**How to try**: Free cloud at app.plane.so, or self-host with Docker / Kubernetes (docs at developers.plane.so).

### 7. n8n-io/n8n
**What it does**: Fair-code (source-available) workflow automation platform with strong native AI support. Visual canvas + custom JS/Python nodes, 400–1500+ integrations, human-in-the-loop, observability, self-host or cloud.

**Good for**: Anyone building multi-step automations, AI agents that call tools, data pipelines, or business process automation. Especially powerful when you need to self-host for privacy/control or combine AI with existing systems.

**How to try**: `curl -fsSL https://get.n8n.io | sh` or Docker one-liner. Editor at http://localhost:5678. Cloud also available.

### 8. anthropics/claude-code
**What it does**: Anthropic’s official agentic coding tool that lives in the terminal (also IDE / GitHub). Understands the whole codebase, executes routine tasks, explains complex code, manages git workflows — all through natural language.

**Good for**: Claude users who want deep, context-aware coding assistance directly in the terminal or IDE without switching tools. Strong at multi-file understanding and git operations.

**How to try**: `curl -fsSL https://claude.ai/install.sh | bash` (or brew / WinGet). Then `claude` in a project directory.

### 9. AprilNEA/OpenLogi
**What it does**: Fully local, native Rust alternative to Logitech Options+. Remaps buttons, controls DPI / SmartShift, gestures, Litra lights, webcam settings (UVC), per-app profiles, RGB, etc. over HID++. No account, no telemetry, plain TOML config.

**Good for**: Privacy-conscious users, Linux users, and power users of Logitech mice/keyboards/webcams who want full control without Logitech’s cloud software.

**How to try**: Build from source or check releases; configuration via TOML + CLI.

### 10. modular/modular
**What it does**: Open-source components of the Modular Platform: MAX (high-performance inference engine / OpenAI-compatible server + model pipelines) and the Mojo programming language (systems language designed for AI with Python interop).

**Good for**: AI engineers who want faster inference, custom model serving, or a language that combines Python ease with systems performance for ML workloads.

### 11. ripienaar/free-for-dev
**What it does**: Long-running, community-maintained curated list of SaaS, PaaS, and IaaS services that offer useful free tiers for developers, DevOps, and infrastructure work.

**Good for**: Bootstrapping projects, students, open-source maintainers, or anyone hunting free (or free-for-a-year) infrastructure, monitoring, CI, auth, databases, etc. without researching every vendor.

### 12. PostHog/posthog
**What it does**: Open-source suite for product analytics, session replay, feature flags, A/B experiments, error tracking, logs, and AI observability. Can be steered from Slack / web / desktop / MCP. Self-host or cloud.

**Good for**: Product and engineering teams that want full ownership of their product data and the ability to run experiments and diagnostics without sending everything to a third-party SaaS.

---

## How to “Deploy / Test at a Time of Your Choosing”

1. **This repository itself is the persistent deployment of the report**. Bookmark, star, or fork https://github.com/jalliance/github-trending-2026-08-23. The content will remain available indefinitely.
2. Most of the projects above are **not** single-click web apps. They are libraries, CLIs, frameworks, or self-hostable services. To actually run any of them:
   - Follow the “How to try” notes above, or
   - Tell us *which specific repository* you want to experiment with and under what constraints (local Docker, cloud instance, specific feature, etc.). We can then provide exact commands, docker-compose, or deployment guidance.
3. If you want ongoing monitoring, we can create a Grok Automation that re-scrapes GitHub Trending on a schedule (daily/weekly) and updates a report or notifies you.

**Caveats**  
- Star counts and rankings move fast; this is a point-in-time snapshot.  
- Many top entries are meta-tooling for AI coding agents — the current market is heavily skewed that way.  
- “Deploy everything” is not practical; pick one or two that match your actual needs.

Generated by the Grok team (Best / Grok / Brutal / Lucas) for later review and testing.
