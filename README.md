# Shawn M. Sorrell

I build AI systems that work in production, and I've developed a methodology for making that reliable.

Over two years I built a one-person AI engineering practice inside a legacy enterprise — 8 production systems, 5 MCP servers, a critical security audit — with no engineering team, no CI/CD, and no code review. The systems are real (daily users, live data, production databases), but the part I care about most is the methodology I built to make agent-driven engineering trustworthy: governance documents, spec-first workflows, safety harnesses, session architecture patterns, and trust ordering hierarchies — all pressure-tested across 310+ agentic sessions, 24,000+ turns, and 4 platforms.

**Open to applied AI / forward-deployed engineering roles. Remote or relocation.**

---

## How I Work With Agents

I don't use AI coding tools casually. I've developed a systematic methodology for agent governance, refined across Claude Code, Amp, Cursor, and Gemini:

- **AGENTS.md governance documents** in every project — 13 files across 7 projects, evolving from 78-line templates to 465-line specs with MCP security directives, trust ordering hierarchies, and per-server permission tiers
- **Spec-driven development** — 53% of agentic threads follow a spec-before-implementation pattern; specs, QA prompts, and audit protocols are first-class project artifacts
- **7 distinct safety layers** — dry-run modes, JSONL audit logging, two-phase confirmation (single-use tokens + TTL), filesystem kill switch, trust ordering, MCP permission tiers, supervisor gates
- **Session architecture** — persistent state (MEMORY.md, DEVLOG.md), phase-specific init templates, multi-phase campaign workflows
- **Workflow ratio** — 33% review/audit/verification, 16% spec/design/architecture, 11% implementation. The agent writes the code; I govern the process.

## What I've Shipped

### MCP Servers (5 production)

- **[superhuman-cli](https://github.com/GodHelpThisCoder/superhuman-cli)** — 46-tool TypeScript/Bun MCP server for Superhuman email via CDP. 328 tests. 7 safety layers. Public.
- **PCPartPicker MCP** — 14-tool TypeScript server. 5-round QA cycle, 48-finding documentation audit.
- **Amazon MCP** — 9-tool TypeScript server with safety-gated purchase flows.
- **Google Drive + Sheets MCP Bridge** — Two-tier Bun/TypeScript + Apps Script. JAIL_ROOT boundary, supervisor approval, rollback. 8 milestones.
- **UI Color Extraction MCP** — Python/Pillow/scikit-learn/OpenCV. k-means + DBSCAN.

### Enterprise Systems (Capital Vacations, all self-initiated)

- **Sales Intelligence Dashboard** — FastAPI/SQLite/Playwright/React. Power BI + Sheets → SQLite datamart → HTTPS dashboard. 20+ daily users.
- **Database Security Audit** — Found critical dbo-level access across production SQL Server. Documented blast radius, wrote remediation plan, disclosed to CTO/CXO/IT. Converted potential adversarial situation into remediation partnership.
- **Document Archive** — Scanner → OCR classifier → SOP-compliant filing. Cleared 3-month backlog in 3 days.
- **Meeting Intelligence** — Conference mic → Gemini Flash (transcription) → Claude Opus (structured notes, action items).
- **SQL Server Automation** — Python/pyodbc with mock mode, parameterized queries, audit logging, pre-flight checks, explicit transactions.
- **Gifting Automation** — 8 min/tour → 2 min. Deployed to regional staff.

### Learning Systems

- **Eubathron** — AI tutoring system for 49 ML/robotics papers at 5 reading levels. 200+ spec files. 310-line AGENTS.md.
- **Ilya List** — React 19/D3.js curriculum portal with DAG prerequisite mapping.

## Stack

**Languages:** TypeScript, Python, SQL, Bash
**AI/ML:** Claude API, Gemini API, MCP protocol, OpenVINO/ONNX, OCR pipelines
**Agent Platforms:** Claude Code (Opus), Amp, Cursor, Gemini
**Web:** React 19, FastAPI, Bun, Vite, D3.js, Tailwind, Playwright
**Data:** SQLite, SQL Server (pyodbc), Google Sheets API, Power BI
**Infra:** Docker, Ansible, Traefik, Tailscale, Hetzner Cloud, Matrix/Synapse
**Methodology:** AGENTS.md governance, spec-driven development, multi-round QA, session architecture, safety-by-design, trust ordering

## Contact

**Email:** shawnmsorrell@gmail.com
**Location:** East Tennessee — open to remote or relocation
