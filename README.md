# Vibes

A repository demonstrating what's possible with AI coding assistants using dev containers. This setup includes [Claude Code](https://www.anthropic.com/claude-code), [OpenAI Codex CLI](https://github.com/openai/codex), and [Google Gemini CLI](https://github.com/google-gemini/gemini-cli).

## Setup

### Dev Container Setup
1. Fork this repository
2. Open in your preferred dev container environment:
   - **VS Code**: Use the "Reopen in Container" command
   - **GitHub Codespaces**: Create a new Codespace
   - **Local Docker**: Run `docker compose up` if you have docker-compose.yml

3. Set your API keys as environment variables:
   - `ANTHROPIC_API_KEY` - Get from [Anthropic Console](https://console.anthropic.com/keys)
   - `OPENAI_API_KEY` - Get from [OpenAI Platform](https://platform.openai.com/api-keys) 
   - `GEMINI_API_KEY` - Get from [Google AI Studio](https://aistudio.google.com/apikey) (generous free tier!)

## Available CLIs

### Claude Code (Anthropic)
```bash
claude
claude "What does this repository do?"
```

### Codex CLI (OpenAI)
```bash
codex "Generate a Python function to sort a list"
```

### Gemini CLI (Google)
```bash
gemini "Explain this code"
```
*Note: Gemini CLI currently offers a generous free tier, making it great for experimentation.*

## Agentic Prompting Resources

- [CLAUDE.md](./CLAUDE.md) - Claude-specific prompting techniques
- [GEMINI.md](./GEMINI.md) - Gemini prompting best practices  
- [AGENTS.md](./AGENTS.md) - General agentic prompting strategies

## Troubleshooting

If you encounter API key issues:

1. Ensure your API keys are properly set as environment variables
2. For dev containers, you may need to rebuild the container after adding keys
3. Set keys for your current session:
   ```bash
   export ANTHROPIC_API_KEY=your-api-key-here
   export OPENAI_API_KEY=your-openai-key-here
   export GEMINI_API_KEY=your-gemini-key-here
   ```