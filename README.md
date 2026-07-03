# sum-ghud-shkills 👋

Hey there! Welcome to my little corner of the internet.

This repo is where I stash the **good stuff** — handy `skills.md` files, agent configs, coding helpers, and other little goodies I've picked up (or built myself) while tinkering with AI coding tools and dev workflows.

Think of it as a junk drawer, but make it *useful*. 🛠️

## What's inside?

Mostly markdown files and config snippets that pair well with tools like **opencode**, **Claude Code**, **Cline**, and friends. Stuff that makes my AI pair-programmer behave a little more like a teammate and a little less like a slot machine.

## A peek at what's here

### 🎧 `listen-plan-build` (my opencode agent)

One of my favourites. I made a custom **listen agent** for opencode so I can run a tight little loop:

1. **Listen** — I dump a thought, a rough idea, or a half-baked requirement.
2. **Plan** — the agent turns my rambling into a clean, ordered plan.
3. **Build** — I (or another agent) goes and ships it.

It's like rubber-ducking, except the duck actually writes the bullet points. 🦆✅

📂 The agent lives at [`agents/listen.md`](agents/listen.md) — the folder layout mirrors opencode's own `~/.config/opencode/agents/` so you can drop it straight in.

**What it does (in short):**
- Acts as a requirements analyst — reads, asks, and clarifies.
- Writes a running `session-*.md` doc so nothing gets lost in translation.
- Refuses to plan or build on its own — that's the next agent's job.

More skills and helpers will land here as I cook them up. PRs, ideas, and "hey, you forgot this one" messages are all very welcome.

Happy hacking! 🚀
