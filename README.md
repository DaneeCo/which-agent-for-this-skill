# Which Agent For This

**Brought to you by [Danee Co](https://www.linkedin.com/in/daneechavez), creative operations and AI enablement consultant.**

A Claude skill that tells you which AI agent to use for a job. Describe the chore, and it names the agent, why, the exact text to send it, and the one catch to watch for. It runs on a map built from hands-on testing of Instinct, dot, Grokbot, Claude with Duet and Muse, dated November 24, 2026.

## What it does

You describe what you want done in plain words: watch a price, buy at an exact time, roll up a noisy group chat, share one agent with your family. The skill restates the real job, checks it against the tested map, and picks the simplest agent that fits what you already have.

If the job spends money, messages people as you, or needs big permissions, it tells you to set the agent to ask first. If the map doesn't cover the job, it says so and labels its answer as reasoning, not a test result.

## When it runs

- "Which agent should I use for this?"
- "What app should I use to watch Black Friday prices?"
- "Can an agent do X for me?"
- "Should I use Grok or dot for my group chats?"
- Any time you describe a chore and want a tool pick, even without saying "agent".

## What you get

- **Use:** the agent, plus a runner-up.
- **Why:** one sentence tied to what happened in testing.
- **Say this:** a one-line text you can send the agent.
- **Watch out:** the biggest catch for that job.
- **As of:** the map's date, because these tools change monthly.

## Principles

- One job: pick the agent. No setup lectures.
- Connector first, screen agent only when there's no connector.
- Never invent a feature, price or result.
- Under 120 words per answer.
- The map lives in `references/agent-map.md`. Update that file and its date, and leave the steps alone.

## Install

Download `which-agent-for-this-v1.zip`, unzip it, and upload the whole `which-agent-for-this-v1/` folder in Claude under Settings, Capabilities, Skills. Keep the `references/` and `examples/` folders with it.

## License

MIT

---

Built by Danee Co. If this saved you time, tell me what landed: https://www.linkedin.com/in/daneechavez
