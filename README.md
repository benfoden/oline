[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](CHANGELOG.md)
[![ClawHub](https://img.shields.io/badge/Install-ClawHub-orange)](https://clawhub.ai/benfoden/oline)

# Oline

Made to align your actions with *your* goals.


---

## How this idea started

This started as a frustration.

Most productivity tools (and LLMs generally) are built around the idea that you know what you want and just need help doing more of it. All optimized for output. What they miss is the prior question: *is this even the right input?*

The idea behind Oline is simple. Before anyone or any tool can help you move faster, they need to understand where you actually want to go. And you need to understand too. This is not the answer you give when someone asks "what are your goals?" but the real signal buried in what lights you up, what you quietly avoid, what you'd protect if everything else had to go. That takes time to uncover and it takes the kind of awareness that compounds across conversations.

Oline works inside your favorite AI agent or chat. It doesn't track tasks or send you reminders to drink water. It notices what you value, watches how that lines up with how you're actually spending your time, and surfaces the gap gently, without judgment, and when you're ready to hear it.

Oline is about harnessing psychology and technology in service of you and your goals.

[Read the full discussion that built Oline here](https://scrapbox.io/benfoden/Oline_Origin_Story)

---

## What Oline Does

- Discovers what you value through Socratic conversation
- Builds a model of your energy sources, drains, patterns, and ideal self
- Understands tensions between stated values and described behavior
- Identifies recurring friction points and proposes systemic solutionsn where feasible
- Keeps you pointed at what you said matters, across sessions and over time

What it doesn't do: lecture, prescribe, or "hold you accountable" in a cringe way. It's more like a mirror that helps you reframe and see better.


---

## Install

### Option 1: OpenClaw (Recommended)

If you're using [OpenClaw](https://openclaw.ai), install directly via ClawHub:

```bash
npx clawhub@latest install oline
```

This will install the latest version and set up the skill. On subsequent sessions, Oline will be available automatically.

### Option 2: Manual Install

Copy the `oline/` folder to your skills directory:

```bash
# For OpenClaw:
cp -r oline ~/.openclaw/workspace/skills/

# For Claude Code / OpenCode:
# Copy to your workspace's skills folder (see your tool's documentation)
```

### Option 3: Standalone

No installation required. Copy the contents of `standalone/oline-standalone-prompt.md` into your AI's system prompt:

1. Open `standalone/oline-standalone-prompt.md`
2. Copy everything
3. Paste as your first message in Claude, GPT, or any capable AI


---

## Get started

### With OpenClaw

After installing, just start a conversation:

> "Let's do an Oline session." or type `/skill oline`

Oline will introduce itself and begin the first values-elicitation session. State is created automatically under `{workspace}/oline/`.

### Single prompt version for Gemini, ChatGPT, Claude, etc.

Paste the prompt in /standalone into your favorite AI chat and say hello. At the end of each session, ask:

> "Summarize my current profile and trajectory for next time."

Save the response and paste it at the start of your next session to maintain continuity.

---

## Oline Pro (Coming Soon)

The community version gives you a powerful values-alignment companion. But some things are better with more:

- **Systems Engine** — When Oline spots recurring friction, it doesn't just name it. Oline Pro builds actual automations, routines, and reminders to eliminate the friction. No more manual implementation.
- **Trajectory Intelligence** — Your values profile becomes predictive. Oline notices patterns across months, surfacing "you tend to drift from X around this time of year" before you're in it.
- **Session Insights** — After every conversation, a private debrief: what shifted, what patterns emerged, what Oline noticed but didn't say.

Oline Pro is about unlocking the level of personal infrastructure that makes a real difference.

**Early access:** [Join the interest list → https://oline.so/pro](https://oline.so/pro)


---

## Contributing

Oline is open source and welcomes contributions. See [CONTRIBUTING.md](CONTRIBUTING.md) for details — we use the DCO (Developer Certificate of Origin) sign-off model.

Key points:
- Sign off your commits with `git commit --signoff`
- By contributing, you agree contributions may be used in both open source and commercial versions
- Be kind, constructive, and aligned with the mission


---

## License

Licensed under [Apache 2.0](LICENSE). Copyright Oline Contributors.



---

## Questions

This was built for personal use and shared as-is. If something's unclear or you'd like to discuss, open an issue or reach out.


---

## A Note

Oline is a reflective tool, not a therapist. It asks questions and listens. It doesn't diagnose, treat, or provide medical or mental health advice. If you're going through something serious, please talk to a professional.
If you're in crisis: [findahelpline.com](https://findahelpline.com) connects you to support in your country
