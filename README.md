# ✨ Vibe Coding ✨

**Turn imagination into reality with AI coding tools**

A GitHub Codespaces template pre-configured with the latest AI coding agents:
- [Claude Code](https://www.anthropic.com/claude-code) - Anthropic's CLI for Claude
- [OpenAI Codex CLI](https://github.com/openai/codex) - OpenAI's command-line interface
- [Google Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's Gemini CLI

> *"where you fully give in to the vibes, embrace exponentials, and forget that the code even exists"* - Andrej Karpathy

This repository also includes a presentation on Vibe Coding and AI development tools.

## Quick Start

### 1. Get Your API Keys
Before starting, you'll need API keys for the AI services you want to use:
- **Claude Code**: Get your key from [Anthropic Console](https://console.anthropic.com/keys)
- **OpenAI Codex**: Get your key from [OpenAI Platform](https://platform.openai.com/api-keys)
- **Gemini CLI**: Get your key from [Google AI Studio](https://aistudio.google.com/app/apikey)

### 2. Launch Your Codespace
1. Fork this repository
2. Click the green "Code" button → "Codespaces" → "Create codespace on main"
3. Choose "US West" or "Southeast Asia" region for optimal performance

### 3. Set Up Your API Keys
**Option A: During Codespace Creation**
- When prompted, enter your API keys during the setup process

**Option B: Using GitHub Secrets (Recommended)**
- Go to [GitHub Codespaces Settings](https://github.com/settings/codespaces)
- Add these secrets:
  - `ANTHROPIC_API_KEY` - Your Claude API key
  - `OPENAI_API_KEY` - Your OpenAI API key  
  - `GEMINI_API_KEY` - Your Gemini API key

**Option C: Set Manually in Terminal**
```bash
export ANTHROPIC_API_KEY=your-claude-key-here
export OPENAI_API_KEY=your-openai-key-here
export GEMINI_API_KEY=your-gemini-key-here
```

## Using the AI Coding Tools

Once your Codespace is set up, you can use any of the AI coding assistants:

### Claude Code
```bash
claude
# or with a specific question
claude "What does this repository do?"
```

### OpenAI Codex CLI
```bash
codex
# or with a prompt
codex "Create a Python function to sort a list"
```

### Gemini CLI
```bash
gemini
# or with a query
gemini "Explain this code"
```

## Presentation

This repository includes a presentation about Vibe Coding and AI development tools. To generate and view the slides:

```bash
pnpm install
pnpm run slides
```

Then open `index.html` in your browser to view the presentation.

## Vibe Coding Tips & Tricks

From the presentation, here are some pro tips for AI coding:

- **Geminiception**: Call Claude or Gemini from within their own canvas/artifacts
- **YOLO Mode**: For the brave and adventurous
- **MCP**: Give your agents more tools - [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/c19925b8f0f2815ad72b08d2368f0007c86eb8e6/src/puppeteer) is excellent for app screenshots
- **Checkpoints**: Use `git` frequently - ask agents to commit their changes
- **Linting & Testing**: Ask for linting and tests to give models feedback
- **Prompt Engineering**: Create `AGENTS.md`, `GEMINI.md`, `CLAUDE.md` files for context
- **Git Worktrees**: Run [parallel Claude Code sessions](https://docs.anthropic.com/en/docs/claude-code/common-workflows#run-parallel-claude-code-sessions-with-git-worktrees)

## Troubleshooting

**Missing API Keys:**
- Follow on-screen setup instructions
- Rebuild your Codespace after adding secrets
- Set keys manually: `export ANTHROPIC_API_KEY=your-key-here`

**Performance Issues:**
- Use US West or Southeast Asia regions
- Ensure stable internet connection