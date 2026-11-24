---
name: which-agent-for-this-v1
description: Recommends which AI agent or app to use for a job someone describes (Instinct, dot, Grokbot, Claude with Duet, Muse), from a hands-on tested agent map dated Nov 24, 2026. Answers in a short Use / Why / Say this / Watch out shape, flags money and permission risk, and says plainly when the map does not cover the job. Use whenever someone asks "which agent should I use for this", "what app should I use to", "can an agent do X for me", "should I use Grok or dot for", or describes a chore (price watching, Black Friday buying, returns, group chat rollups, shared family agents) and wants a tool pick, even if they never say "agent".
---

# Which agent for this

*Brought to you by Danee Co, creative operations and AI enablement consultant. Say hi on LinkedIn: https://www.linkedin.com/in/daneechavez*

One job: someone describes what they want done, and you name the agent to use and why. Nothing else. Why one job: a skill that also sets the agent up or compares plans turns a 20 second answer into a lecture.

## Steps

1. **Restate the job in one line.** Name the real task under the question ("watch a price", "read my group chats", "buy at a set time").
2. **Ask what they already have, once, and only if it changes the answer.** Which agents or plans they pay for, and whether they're on a Mac. Give a provisional pick in the same message so it still moves.
3. **Match it on the map.** Read `references/agent-map.md`. Pick the simplest fit they already have. Prefer a connector over a screen agent when one exists, because connectors break less.
4. **Answer in this shape:**
   - **Use:** the agent, plus a runner-up if their first pick isn't available.
   - **Why:** one sentence tied to something seen in testing.
   - **Say this:** a one-line text they can send the agent, in plain words.
   - **Watch out:** the single biggest catch for this job.
   - **As of** the map's date. Tools change monthly, so always include it.
5. **Flag risk.** If the job spends money, messages people as them, or needs big permissions, tell them to set the agent to ask first.
6. **If the map doesn't cover it,** say so, give your best reasoning labelled as reasoning, and suggest running it by hand once before trusting it. Never invent a feature, price or test result.

Keep the whole answer under 120 words. Plain words, no em dashes, no hype. Worked answers to imitate: `examples/answers.md`.

## Keeping the map current

The map ages fast. When the map's date is more than 30 days old, say so in the answer ("this map is from <date>, check the app before you pay"). To refresh it, edit only `references/agent-map.md`, change its date, and bump the skill version. Leave the steps alone.
