---
marp: true
theme: gaia
backgroundColor: #1a1a1a
color: #fff
style: |
  @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@400;700&display=swap');

  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  section {
    font-family: 'Roboto Mono', monospace;
    padding: 100px;
    background: linear-gradient(-45deg, #1a1a1a, #2c3e50, #34495e, #2c3e50);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 15px;
  }

  section::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle, rgba(255,255,255,0.05) 0%, rgba(255,255,255,0) 70%);
    pointer-events: none;
  }

  h1, h2 {
    font-family: 'Orbitron', sans-serif;
    color: #00ffcc;
    text-align: center;
    text-shadow: 0 0 10px #00ffcc, 0 0 20px #00ffcc, 0 0 30px #00ffcc, 0 0 40px #00ffcc;
    animation: fadeIn 1s ease-in-out;
  }

  h3 {
    font-family: 'Orbitron', sans-serif;
    color: #ff66ff;
    text-shadow: 0 0 5px #ff66ff, 0 0 10px #ff66ff;
  }

  ul, p, li {
    animation: fadeIn 1.5s ease-in-out;
  }

  .split {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    animation: fadeIn 2s ease-in-out;
  }

  .split ul {
    font-size: 0.75em;
    background: rgba(0, 0, 0, 0.2);
    padding: 20px;
    border-radius: 10px;
    border: 1px solid rgba(255, 255, 255, 0.1);
  }

  .split h3 {
    font-size: 1em;
  }

  a {
    color: #00aaff;
    text-decoration: none;
    transition: color 0.3s ease, text-shadow 0.3s ease;
  }

  a:hover {
    color: #ffab00;
    text-shadow: 0 0 5px #ffab00;
  }
---

# ✨ Vibe Coding ✨

### Let's turn imagination into reality

**Chris Van Pelt, Weights & Biases**

---

## Who am I?

- Founding member of **Weights & Biases**
- Building AI dev tools in SF since 2006
- I ❤️ Vibe Coding

---

## What is Vibe Coding?

> "where you fully give in to the vibes, embrace exponentials, and forget that the code even exists"

**- Andrej Karpathy**

---

## The AI Coding Tool Explosion 🚀

This space is growing incredibly fast!

![bg right:40%](./assets/vertical-agentic-coding.png)

---

## Your AI Coding Toolkit

<div class="split">
<div>

### Chat Agents
- ChatGPT Canvas
- Claude Artifacts*
- Gemini Canvas*

### Web Agents
- v0.dev
- lovable.dev
- bolt.new

</div>
<div>

### CLI Agents
- Claude Code
- OpenAI Codex CLI
- Gemini CLI

### IDE Agents
- Github CoPilot
- Cursor
- Windsurf

</div>
</div>

---

## Tips & Tricks

- **Geminiception:** Call Claude or Gemini [from within](https://simonwillison.net/2025/Jun/26/geminiception/) their own canvas/artifacts.
- **YOLO Mode:** For the brave and adventurous.
- **MCP:** Give your agents more tools.  [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/c19925b8f0f2815ad72b08d2368f0007c86eb8e6/src/puppeteer) is excellent for giving app screenshots.
- **Checkpoints:** `gh` / `git` is your friend.  Ask the agent to commit their changes.
- **Linting & Testing:** Ask for linting and tests to give the model feedback on changes

---

## L33t Ultra Vibez

- **Prompt Engineering:** AGENTS.md, GEMINI.md, CLAUDE.md, Cursor rules... they are all :fire:
- **Reasoning:** Ask the model to "think carefully" for trickier problems.
- **Mobile:** [expo](https://expo.dev) is great for cross-platform mobile apps. [iOS Simulator MCP](https://github.com/joshuayoes/ios-simulator-mcp) == :rocket:
- **Commands:** [Custom Claude slash commands](https://docs.anthropic.com/en/docs/claude-code/slash-commands#custom-slash-commands) are :sunglasses:
- **Git worktrees:** Start [vibing in parallel](https://docs.anthropic.com/en/docs/claude-code/common-workflows#run-parallel-claude-code-sessions-with-git-worktrees)! Try giving `gemini`, `claude`, and `codex` the same task.

---

## Tonight's Goal

1.  **Create a small AI project** in a short time.
2.  Bonus points for intergrating **weave**
3.  Let's have fun and embrace the vibes!

---

## Coming Up Next...


### ⚡️ Demos ⚡️
### 🔥 Awards 🔥

---

## Let's get started!

### Questions?
