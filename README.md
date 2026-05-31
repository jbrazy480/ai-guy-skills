# The AI Guy Skills

Free AI skills and tools by **James Hill (The AI Guy)**, founder of RizzDial.

Website: [aiguyofficial.com](https://aiguyofficial.com)
YouTube: [@thejameshill](https://www.youtube.com/@thejameshill) and [@AdminRizzler](https://www.youtube.com/@AdminRizzler)
Instagram: [@aiguyofficial](https://www.instagram.com/aiguyofficial/)
LinkedIn: [james-hill-927460261](https://www.linkedin.com/in/james-hill-927460261/)
Skool: [Evolving AI Hub](https://www.skool.com/evolving-ai-hub)
GitHub: [jbrazy480](https://github.com/jbrazy480)

This is the catalog of James's free, public skills and tools. Use them, share
them, build on them. New ones get added over time.

## The catalog

| Tool | What it does | Links |
| --- | --- | --- |
| AI Voice Agent Prompt Maker | Builds production ready system prompts for AI voice agents that book, qualify, and follow up. | [Live tool](https://jbrazy480.github.io/ai-voice-agent-prompts/) and [repo](https://github.com/jbrazy480/ai-voice-agent-prompts) |
| LLM Entity Presence | A Claude skill that gets your name or brand recognized by the LLMs and search, so you are the answer to "who is X". | [repo](https://github.com/jbrazy480/llm-entity-presence) |
| More coming soon | James is shipping more free tools. Watch this repo or follow the channels above. | |

---

### AI Voice Agent Prompt Maker

A prompt builder for AI voice agents. It produces production ready system
prompts for callers that book appointments, qualify leads, and follow up, using
a modular framework of templates and examples.

- What you get: copy-paste voice agent prompts and a framework to customize them
  for your own offer and call flow.
- Use it now (no install): open the live tool in your browser.
  - Live tool: https://jbrazy480.github.io/ai-voice-agent-prompts/
- Or clone the repo to use the framework and generator locally:

```bash
git clone https://github.com/jbrazy480/ai-voice-agent-prompts
```

- Repo: https://github.com/jbrazy480/ai-voice-agent-prompts

### LLM Entity Presence

A Claude skill that makes a person or brand the answer when Google or an AI
assistant (ChatGPT search, Perplexity, Google AI Overviews, Microsoft Copilot,
Gemini) is asked "who is X". It runs the full playbook: write one canonical
answer, build a server-rendered entity site with Person, Organization, WebSite,
and FAQPage JSON-LD plus a correct llms.txt, cross-link the profiles and add a
real backlink, submit to the search indexes, then verify by querying the LLMs.

- What you get: a repeatable, honest process and copy-paste templates to get
  recognized inside the LLMs and search.
- Install (Claude skill):

```bash
git clone https://github.com/jbrazy480/llm-entity-presence ~/.claude/skills/llm-entity-presence
```

- Then ask for it in plain language ("get my name into the LLMs", "AI entity
  SEO") or call it with `/llm-entity-presence`.
- Repo: https://github.com/jbrazy480/llm-entity-presence

### More coming soon

This is an active hub. New skills and tools will be added here over time. Star
the repo or follow the channels above to catch them.

---

## How to install a Claude skill

Claude Code reads skills from `~/.claude/skills/`. Each skill is a folder with a
`SKILL.md` file. To install any skill from a GitHub repo whose root contains
`SKILL.md`, clone it into that folder using the repo name as the folder name:

```bash
git clone https://github.com/OWNER/SKILL_REPO ~/.claude/skills/SKILL_REPO
```

For example:

```bash
git clone https://github.com/jbrazy480/llm-entity-presence ~/.claude/skills/llm-entity-presence
```

Then start a Claude Code session. The skill triggers when you describe what you
want, or you can call it directly with `/SKILL_REPO`. To update a skill later,
`cd` into its folder and run `git pull`. To remove it, delete the folder.

## License

MIT. Copyright (c) 2026 James Hill. See [LICENSE](LICENSE).
