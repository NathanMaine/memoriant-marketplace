<p align="center">
  <h1 align="center">Memoriant Marketplace</h1>
  <p align="center">Curated Claude Code plugins for patent workflow, code quality, architecture, compliance, and developer experience.</p>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/plugins-14-blue" alt="14 Plugins" />
  <img src="https://img.shields.io/badge/categories-9-green" alt="9 Categories" />
  <img src="https://img.shields.io/badge/platform-Claude_Code-8A2BE2" alt="Claude Code" />
  <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT" />
</p>

## Add This Marketplace

```bash
/plugin marketplace add NathanMaine/memoriant-marketplace
```

Then install any plugin:

```bash
/plugin install memoriant-patent-skills@memoriant-marketplace
```

---

## Plugins by Category

### Legal & Intellectual Property

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-patent-skills](https://github.com/NathanMaine/memoriant-patent-skills)** | `/install NathanMaine/memoriant-patent-skills` | Full patent workflow: prior art search (USPTO 7-step), patentability analysis (101-112), application drafting (provisional/non-provisional/PCT), review, and diagram generation. 6 skills + 4 agents. |

### Code Quality

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-test-coverage-skill](https://github.com/NathanMaine/memoriant-test-coverage-skill)** | `/install NathanMaine/memoriant-test-coverage-skill` | AST-powered test coverage analysis. Scans source and test directories, identifies untested functions, and generates test skeletons automatically. |

### Architecture

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-architecture-review-skill](https://github.com/NathanMaine/memoriant-architecture-review-skill)** | `/install NathanMaine/memoriant-architecture-review-skill` | Accepts architecture briefs and generates structured design reviews with risk assessments, open questions, and compliance checklists. |

### Documentation

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-docforce-skill](https://github.com/NathanMaine/memoriant-docforce-skill)** | `/install NathanMaine/memoriant-docforce-skill` | Detects documentation drift by comparing code and config against docs. Finds stale documentation with severity labeling and evidence logging. |

### Developer Experience

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-env-bootstrap-skill](https://github.com/NathanMaine/memoriant-env-bootstrap-skill)** | `/install NathanMaine/memoriant-env-bootstrap-skill` | Scans a project folder and generates a bootstrap script and onboarding checklist for new developer environments. |
| **[memoriant-screen-recorder-skill](https://github.com/NathanMaine/memoriant-screen-recorder-skill)** | `/install NathanMaine/memoriant-screen-recorder-skill` | Screen recording from Claude Code. Guided 6-step flow: preflight check, window picker (lists all open windows), save location, record, format selection (video/GIF/both). Records specific windows via ffmpeg real-time crop. |

### Testing & Performance

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-perf-test-skill](https://github.com/NathanMaine/memoriant-perf-test-skill)** | `/install NathanMaine/memoriant-perf-test-skill` | Generates load test plans (steady, burst, soak) from service profiles and SLOs, with metrics interpretation and evidence logging. |
| **[memoriant-voice-test-skill](https://github.com/NathanMaine/memoriant-voice-test-skill)** | `/install NathanMaine/memoriant-voice-test-skill` | Stress-tests voice and NLU endpoints with noise injection, intent classification, and robustness reporting. |

### AI Agent Testing

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-eval-sandbox-skill](https://github.com/NathanMaine/memoriant-eval-sandbox-skill)** | `/install NathanMaine/memoriant-eval-sandbox-skill` | Holdout scenario evaluation for AI agents. Doer/Judge/Adversary/Observer roles with probabilistic satisfaction scoring and tamper-proof audit trails. |

### Compliance & Security

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-llm-gateway-skill](https://github.com/NathanMaine/memoriant-llm-gateway-skill)** | `/install NathanMaine/memoriant-llm-gateway-skill` | Compliance-first LLM gateway with policy-as-code enforcement, tamper-evident audit trails, and compliance evidence export for regulated industries. |
| **[memoriant-governance-compiler-skill](https://github.com/NathanMaine/memoriant-governance-compiler-skill)** | `/install NathanMaine/memoriant-governance-compiler-skill` | Compiles governance policy Markdown into directed acyclic graphs for deterministic, auditable policy evaluation. |

### Planning & Orchestration

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-temporal-planner-skill](https://github.com/NathanMaine/memoriant-temporal-planner-skill)** | `/install NathanMaine/memoriant-temporal-planner-skill` | Dependency-ordered task planning and execution with temporal constraint resolution for complex multi-step workflows. |

### DevOps & Operations

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-ops-bot-skill](https://github.com/NathanMaine/memoriant-ops-bot-skill)** | `/install NathanMaine/memoriant-ops-bot-skill` | Multi-provider AI agent remote control. Manage Claude Code, Codex CLI, and Gemini CLI agents from Telegram or Matrix. |

### Data & Integration

| Plugin | Install | What It Does |
|--------|---------|-------------|
| **[memoriant-mcp-data-skill](https://github.com/NathanMaine/memoriant-mcp-data-skill)** | `/install NathanMaine/memoriant-mcp-data-skill` | MCP server for conversational data access to CRM systems, ticket trackers, and databases via natural language queries. |

---

## Also Available

| Package | What | Install |
|---------|------|---------|
| **[memoriant-patent-core](https://github.com/NathanMaine/memoriant-patent-core)** | Python library for patent workflow | `pip install memoriant-patent-core` |
| **[memoriant-patent-platform](https://github.com/NathanMaine/memoriant-patent-platform)** | Full self-hosted patent platform | `docker compose up` |

---

## Cross-Platform

All plugins also work with:
- **OpenAI Codex CLI** — via AGENTS.md
- **Google Gemini CLI** — via gemini-extension.json

---

## Contributing

Want to add a plugin to this marketplace? See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

All plugins are [MIT](LICENSE) licensed.

Built by [Nathan Maine](https://github.com/NathanMaine) | [Memoriant](https://memoriant.com)
