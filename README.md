# Cairn

Orchestrate coding agents with full visibility and control.

[![Documentation](https://img.shields.io/badge/docs-cairn.computer-blue)](https://cairn.computer/docs)

Cairn is a desktop app for orchestrating Claude-powered coding agents. Structure work as issues, watch agents plan and implement in real-time, and review the resulting pull requests.

## Features

- **Issue-based workflow** — Structure work as issues with timeline tracking through plan → build → PR stages
- **Live transcripts** — Watch agent reasoning and actions as they happen
- **Isolated git worktrees** — Each implementation runs in its own worktree, preventing conflicts
- **Recipes** — Define multi-agent workflows as reusable graphs
- **GitHub integration** — Real-time PR status, CI checks, and merge/close from the app
- **Session continuity** — Pause and resume conversations without losing context

## Installation

### Prerequisites

- [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) installed (`claude` command available)
- Git installed
- GitHub account (for PR features)

### Download

Download from [GitHub Releases](https://github.com/bleugreen/cairn-releases/releases/latest):

| Platform | File |
|----------|------|
| macOS (Apple Silicon) | `Cairn_x.x.x_aarch64.dmg` |
| macOS (Intel) | `Cairn_x.x.x_x64.dmg` |
| Windows | `Cairn_x.x.x_x64-setup.exe` |
| Linux | `Cairn_x.x.x_amd64.AppImage` or `.deb` |

## Quick Start

1. **Launch Cairn** and complete the onboarding checklist (including GitHub App setup)
2. **Add a project** — Select a git repository from your filesystem
3. **Create an issue** — Press `c` and describe what you want to build
4. **Watch the workflow** — Plan → Build → PR, all with live transparency

See the [Getting Started guide](https://cairn.computer/docs/getting-started) for detailed walkthrough.

## Learn More

- [Getting Started](https://cairn.computer/docs/getting-started) — Full setup and first issue walkthrough
- [Recipes](https://cairn.computer/docs/recipes) — Create multi-agent workflows
- [GitHub Events](https://cairn.computer/docs/github-events) — Trigger workflows from GitHub activity

## Core Concepts

- **Issues** — Units of work with a timeline of jobs (plan, implementation, PR)
- **Recipes** — Workflow graphs that orchestrate multiple agents in sequence or parallel
- **Agents & Skills** — Customizable personas and injectable expertise for specialized tasks

## Links

- [Documentation](https://cairn.computer/docs)
- [Getting Started](https://cairn.computer/docs/getting-started)
- [Report Issues](https://github.com/bleugreen/cairn-releases/issues)
