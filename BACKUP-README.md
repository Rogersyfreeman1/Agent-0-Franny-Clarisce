# Agent 0 - Franny Clarice Backup
## Created: August 16, 2026

---

## What We Built Today

### Agent: Franny Clarice (he/him)
- **Role:** Hyper Task Master, Engineer, Stock Market Investor
- **Personality:** Energetic, systematic, long-term thinker
- **Skills:** 167 total from multiple sources

---

## Skills Breakdown

### 1. Agent Zero Skills (67)
**Location:** `.opencode/skills/` (copied from `agent-zero/plugins/`)
- Plugin management (create, debug, review, contribute)
- Agent creation and management
- Browser automation
- Code execution
- Desktop control
- Email integration
- Memory management
- Task scheduling
- Telegram/WhatsApp integration
- Text editor
- Time travel (version history)
- And more...

### 2. Herdr Skills (1)
**Location:** `.opencode/skills/herdr/` (cloned from `herdr/skills/`)
- Terminal multiplexer control
- Multi-agent orchestration

### 3. Orca Skills (7)
**Location:** `.opencode/skills/` (cloned from `orca/skills/`)
- computer-use
- linear-tickets
- orca-cli
- orca-emulator
- orca-emulator-android
- orca-linear
- orca-per-workspace-env
- orchestration

### 4. Claude Code Skills (47)
**Official Anthropic (17):**
- algorithmic-art, brand-guidelines, canvas-design
- claude-api, doc-coauthoring, docx
- frontend-design, internal-comms, mcp-builder
- pdf, pptx, skill-creator
- slack-gif-creator, theme-factory
- web-artifacts-builder, webapp-testing, xlsx

**Community (30):**
- artifacts-builder, changelog-generator
- competitive-ads-extractor, composio-skills
- connect, connect-apps, connect-apps-plugin
- content-research-writer, developer-growth-analysis
- document-skills, domain-name-brainstormer
- file-organizer, image-enhancer
- invoice-organizer, langsmith-fetch
- lead-research-assistant, meeting-insights-analyzer
- raffle-winner-picker, skill-creator
- skill-share, tailored-resume-generator
- template-skill, twitter-algorithm-optimizer
- video-downloader, webapp-testing

### 5. Codex Skills (46)
**System (5):**
- imagegen, openai-docs, plugin-creator
- skill-creator, skill-installer

**Curated (41):**
- aspnet-core, chatgpt-apps, cli-creator
- cloudflare-deploy, define-goal, figma
- figma-code-connect-components, figma-create-design-system-rules
- figma-create-new-file, figma-generate-design
- figma-generate-library, figma-implement-design
- figma-use, gh-address-comments, gh-fix-ci
- hatch-pet, jupyter-notebook, linear
- migrate-to-codex, netlify-deploy
- notion-knowledge-capture, notion-meeting-intelligence
- notion-research-documentation, notion-spec-to-implementation
- openai-docs, pdf, playwright
- playwright-interactive, render-deploy
- screenshot, security-best-practices
- security-ownership-map, security-threat-model
- sentry, speech, transcribe
- vercel-deploy, winui-app, yeet

### 6. Perplexity Skills (10)
- create-skill
- cx-ticket-triage
- data-exploration
- finance-audit-support
- legal-compliance
- legal-contract-review
- marketing-competitive-analysis
- meeting-prep
- research-summarization
- sales-prospecting

---

## Configuration Files

### opencode.json
```json
{
  "$schema": "https://opencode.ai/config.json",
  "default_agent": "franny-clarice",
  "skills": {
    "paths": [
      ".opencode/skills",
      "agent-zero/skills",
      "herdr/skills",
      "orca/skills",
      "claude-skills-official/skills",
      "codex-skills/skills/.curated",
      "codex-skills/skills/.system",
      "perplexity-skills"
    ]
  },
  "agent": {
    "franny-clarice": {
      "description": "Franny Clarice — Hyper Task Master! He is an engineer and stock market investor who manages tasks with high energy, prioritizes work, and crushes goals!",
      "mode": "primary",
      "color": "#FF00FF",
      "steps": 75,
      "permission": {
        "edit": "allow",
        "bash": "ask",
        "task": "allow",
        "websearch": "allow"
      }
    },
    "build": {
      "description": "Main coding agent. Writes and edits code, creates files, runs commands.",
      "mode": "primary",
      "steps": 50
    },
    "plan": {
      "description": "Planning agent. Researches and creates plans before execution.",
      "mode": "primary",
      "steps": 30
    },
    "general": {
      "description": "General-purpose agent for research and non-coding tasks.",
      "mode": "subagent",
      "steps": 30
    },
    "explore": {
      "description": "Codebase explorer. Quickly finds files and answers questions.",
      "mode": "subagent",
      "steps": 20
    }
  }
}
```

### franny-clarice.md
**Location:** `.opencode/agent/franny-clarice.md`

---

## Cloned Repositories

| Repository | Location | Purpose |
|------------|----------|---------|
| Agent Zero | `agent-zero/` | 67 plugin skills |
| Herdr | `herdr/` | Terminal multiplexer |
| Orca | `orca/` | Agent IDE with remote |
| Claude Skills (Official) | `claude-skills-official/` | 17 Anthropic skills |
| Claude Skills (Awesome) | `claude-skills-awesome/` | 30 community skills |
| Codex Skills | `codex-skills/` | 46 OpenAI skills |
| Perplexity Skills | `perplexity-skills/` | 10 Perplexity skills |

---

## How to Use

1. Open "Agent 0" folder in OpenCode
2. Franny Clarice is your default agent
3. He has access to all 167 skills
4. Skills auto-load when relevant to a task

---

## Backup Instructions

To backup this project:
1. Copy the entire "Agent 0" folder
2. Include all cloned repos
3. Include .opencode/ folder with skills and agent config

---

*Created by Jack on August 16, 2026*
