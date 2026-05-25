# Claude Code Crash Course 🚀

> **A hands-on, project-based repository for mastering Claude Code — Anthropic's official CLI for AI-powered software development**

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-CLI-8B5CF6?style=flat-square)](https://docs.anthropic.com/claude-code)
[![Anthropic](https://img.shields.io/badge/Powered%20by-Anthropic-FF6B35?style=flat-square)](https://anthropic.com)

---

## 🧠 About This Repository

This repository provides a complete, project-based exploration of **Claude Code** — Anthropic's powerful CLI that brings AI capabilities directly into your development workflow. Each `project/*` branch covers a specific Claude Code feature or pattern, with commits ordered chronologically for step-by-step learning.

From custom commands to subagents, MCP integrations, hooks, and context engineering — this repo covers the full power of Claude Code.

---

## 💡 What is Claude Code?

**Claude Code** is an interactive command-line interface that integrates Claude's AI capabilities directly into your terminal. It assists with:

- 🔍 Code analysis and understanding
- 🐛 Bug fixing and debugging
- ✨ Feature development and refactoring
- 🤖 Workflow automation via hooks and subagents
- 🔗 External tool integration via MCP

---

## 🚀 Projects

| Branch | Topic | Description |
|--------|-------|-------------|
| `project/custom-commands` | 🔧 Custom Commands | Extend Claude Code with custom slash commands and automated workflows |
| `project/mcp` | 🔗 MCP Integration | Master Model Context Protocol integration with Context7 MCP server |
| `project/context-engineering-mcp` | ⚡ Context Engineering | Optimize context tokens with task-specific MCP configs using `--mcp-config` |
| `project/subagents` | 🤖 Subagents | Build specialized AI sub-agents within Claude Code (e.g. Code Comedy Carl) |
| `project/hooks-notifications` | 🎣 Hooks & Notifications | Automate workflows with sound notifications and event triggers |
| `project/hookhub` | 🏢 Hook Hub | Advanced hook management, organization and orchestration systems |
| `project/output-styles` | 🎨 Output Styles | Customize Claude Code output formatting and response styles |
| `project/skills` | 🧠 Skills | Build reusable Claude Code skill modules |

---

## 📚 What You'll Learn

- Creating and using custom Claude Code commands
- Integrating MCP servers for extended tool access
- Context engineering for token-efficient agent sessions
- Building specialized subagents for domain-specific tasks
- Automating development workflows with hooks and event triggers
- Advanced hook management and orchestration patterns
- Output formatting and style customization

---

## ⚡ Quick Start

### Prerequisites

- Claude Code CLI (`npm install -g @anthropic-ai/claude-code`)
- Git
- Python 3.8+
- Any code editor / IDE

### Setup

```bash
# 1. Clone the repository
git clone https://github.com/rjayswal-pythonista/claude-code-crash-course
cd claude-code-crash-course

# 2. Checkout the topic branch you want to explore
git checkout project/custom-commands   # for custom commands
git checkout project/subagents         # for subagents

# 3. Follow the commits
git log --oneline --reverse            # see all lessons in order
git checkout <commit_hash>             # jump to any lesson
```

### Run Claude Code

```bash
# Start a Claude Code session in your project directory
claude

# Use a specific MCP config (for context-engineering-mcp branch)
claude --mcp-config .mcp-config.json
```

---

## 🗂️ Tech Stack

| Layer | Tools |
|-------|-------|
| **AI CLI** | Claude Code |
| **Protocol** | Model Context Protocol (MCP) |
| **MCP Server** | Context7, custom MCP servers |
| **Automation** | Claude Code Hooks, Event Triggers |
| **Language** | Python 3.8+, Bash |
| **Provider** | Anthropic Claude |

---

## 🏗️ Repository Structure

```
claude-code-crash-course/
├── .claude/
│   ├── commands/        # Custom slash commands
│   └── settings.json    # Claude Code configuration
├── static/              # Banner and static assets
└── project branches     # Each project/* branch = one topic
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a branch: `project/your-claude-code-feature`
3. Commit changes — each commit should be a logical learning step
4. Open a Pull Request against `main`

---

## 📄 License

Licensed under the [Apache License 2.0](LICENSE).

---

<div align="center">

**Built with ❤️ by [Roshan Jayswal](https://github.com/rjayswal-pythonista)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roshan-jayswal-ab4aa382/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat-square&logo=googlechrome&logoColor=white)](https://roshanjayswal-github-io.vercel.app)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:roshanjayswal15@gmail.com)

</div>
