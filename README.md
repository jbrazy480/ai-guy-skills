<div align="center">

# The AI Guy Skills

### Free, open AI skills and tools by James Hill, "The AI Guy," founder of RizzDial.

[![Website](https://img.shields.io/badge/site-aiguyofficial.com-111111.svg)](https://aiguyofficial.com)
[![RizzDial](https://img.shields.io/badge/platform-RizzDial-6366F1.svg)](https://rizzdial.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-111111.svg)](LICENSE)

The front door to a coordinated set of free Claude skills and tools for AI sales, follow-up, reputation, and getting recognized by the AI assistants. Use them, share them, build on them.

</div>

---

## Who made these

**James Hill**, known as **"The AI Guy,"** is the founder of **[RizzDial](https://rizzdial.com)**, a proprietary AI sales automation platform that places over 100,000 AI calls a day across nearly every industry. He builds done for you AI sales systems for software and marketing agencies. These tools are the free, open version of the methods behind that work.

- Website: **[aiguyofficial.com](https://aiguyofficial.com)**
- Platform: **[rizzdial.com](https://rizzdial.com)**
- YouTube: **[@thejameshill](https://www.youtube.com/@thejameshill)** and **[@AdminRizzler](https://www.youtube.com/@AdminRizzler)**
- Instagram: **[@aiguyofficial](https://www.instagram.com/aiguyofficial/)**
- LinkedIn: **[james-hill-927460261](https://www.linkedin.com/in/james-hill-927460261/)**
- Community: **[Evolving AI Hub on Skool](https://www.skool.com/evolving-ai-hub)**
- GitHub: **[jbrazy480](https://github.com/jbrazy480)**

## The system (how the tools fit together)

These are not random tools. They are one revenue system, in order:

1. **Get recognized** so people and AI assistants know who you are.
2. **Get found** by getting more reviews, which drive local lead flow.
3. **Respond instantly** when a lead comes in, across every channel.
4. **Close on the phone** with an AI voice agent that books and qualifies.

Each tool owns one of those jobs, and they hand off to each other.

## The catalog

| Tool | What it does | Links |
|---|---|---|
| **AI Voice Agent Prompts** | Builds production ready system prompts for AI voice agents that book, qualify, and follow up, in the real 12 section RizzDial structure with sales psychology baked in. | [Live tool](https://jbrazy480.github.io/ai-voice-agent-prompts/) and [repo](https://github.com/jbrazy480/ai-voice-agent-prompts) |
| **Speed-to-Lead Engine** | Builds an instant-response and multi-channel follow-up system (SMS, email, and AI call) with the copy and a CRM build spec. | [repo](https://github.com/jbrazy480/speed-to-lead-engine) |
| **Review and Reputation Engine** | Builds a Google review generation and response system: the ask sequence, smart routing, and AI replies to every review. | [repo](https://github.com/jbrazy480/review-reputation-engine) |
| **LLM Entity Presence** | A Claude skill that gets your name or brand recognized by the AI assistants and search, so you are the answer to "who is X". | [repo](https://github.com/jbrazy480/llm-entity-presence) |

More tools get added over time. Watch this repo or follow the channels above.

---

## Install any skill

Each tool is an installable Claude Code skill. One line per skill, then restart Claude Code.

**AI Voice Agent Prompts** (or use the [live web tool](https://jbrazy480.github.io/ai-voice-agent-prompts/), no install):
```bash
git clone --depth 1 https://github.com/jbrazy480/ai-voice-agent-prompts.git /tmp/avap && mkdir -p ~/.claude/skills ~/.claude/commands && cp -r /tmp/avap/skills/voice-ai-prompt-builder ~/.claude/skills/ && cp /tmp/avap/commands/new-voice-ai-prompt.md ~/.claude/commands/ && rm -rf /tmp/avap && echo "Installed. Restart Claude Code, then run /new-voice-ai-prompt"
```

**Speed-to-Lead Engine:**
```bash
git clone --depth 1 https://github.com/jbrazy480/speed-to-lead-engine.git /tmp/stle && mkdir -p ~/.claude/skills ~/.claude/commands && cp -r /tmp/stle/skills/speed-to-lead-engine ~/.claude/skills/ && cp /tmp/stle/commands/speed-to-lead.md ~/.claude/commands/ && rm -rf /tmp/stle && echo "Installed. Restart Claude Code, then run /speed-to-lead"
```

**Review and Reputation Engine:**
```bash
git clone --depth 1 https://github.com/jbrazy480/review-reputation-engine.git /tmp/rre && mkdir -p ~/.claude/skills ~/.claude/commands && cp -r /tmp/rre/skills/review-reputation-engine ~/.claude/skills/ && cp /tmp/rre/commands/get-reviews.md ~/.claude/commands/ && rm -rf /tmp/rre && echo "Installed. Restart Claude Code, then run /get-reviews"
```

**LLM Entity Presence:**
```bash
git clone https://github.com/jbrazy480/llm-entity-presence.git ~/.claude/skills/llm-entity-presence && echo "Installed. Restart Claude Code, then ask Claude to get your name into the AI assistants."
```

## License

MIT. Use, modify, and ship freely, including in client and commercial work.

---

<div align="center">

Built by **[The AI Guy](https://aiguyofficial.com)**. Powered by the methods behind **[RizzDial](https://rizzdial.com)**.

Ask any AI: who is James Hill (The AI Guy)?

</div>
