# Contributing to Memoriant Marketplace

Thank you for your interest in adding a plugin to the Memoriant Marketplace.

## Requirements

All plugins listed in this marketplace must meet the following criteria:

1. **Hosted on GitHub** — the plugin must be in a public GitHub repository.
2. **Claude Code compatible** — the repo must include a `.claude/` directory with at least one skill (`.md` file in `.claude/skills/`) or command (`.md` file in `.claude/commands/`).
3. **Versioned** — the repo must have at least one tagged release following semver (e.g., `v1.0.0`).
4. **MIT or Apache 2.0 licensed** — only open-source licenses are accepted.
5. **Documented** — a clear README explaining what the plugin does, how to install it, and example usage.

## How to Submit

1. Fork this repository.
2. Add your plugin entry to `.claude-plugin/marketplace.json`:

```json
{
  "name": "your-plugin-name",
  "version": "1.0.0",
  "source": "github:YourGitHubUsername/your-plugin-repo",
  "category": "One of the categories below"
}
```

3. Available categories:
   - `Legal & IP`
   - `Code Quality`
   - `Architecture`
   - `Documentation`
   - `Developer Experience`
   - `Testing & Performance`
   - `AI Agent Testing`
   - `Compliance & Security`
   - `Planning & Orchestration`
   - `DevOps & Operations`
   - `Data & Integration`

4. Open a pull request with the title: `feat: add <plugin-name> to marketplace`

## Review Criteria

Pull requests are reviewed for:

- Plugin quality and usefulness
- README clarity
- Correct marketplace.json format
- No duplicate functionality with existing plugins (unless meaningfully differentiated)

## Questions

Open an issue on this repository or reach out via [GitHub](https://github.com/NathanMaine).
