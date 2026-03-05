[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](CHANGELOG.md)
[![ClawhHub](https://img.shields.io/badge/Install-ClawhHub-orange)](https://clawhub.com)

# Oline

*Solving human alignment: Oline aligns your actions with your goals.*

---

## Origin Story

This started as a frustration.

Most productivity tools are built around the assumption that you already know what you want and just need help doing more of it. Systems, trackers, dashboards — all optimized for output. What they miss is the prior question: *is this even the right output?*

The insight behind Oline is simpler. Before anyone can help you move faster, they need to understand where you actually want to go — not the answer you give when someone asks "what are your goals?" but the real signal buried in what lights you up, what you quietly avoid, what you'd protect if everything else had to go. That takes time. It takes listening. It takes the kind of attention that compounds across conversations.

Oline is that listener, built into your AI. It doesn't track tasks or send you reminders to drink water. It builds a model of what you value, watches how that lines up with how you're actually spending your time, and surfaces the gap — gently, without judgment — when you're ready to hear it.

The name is short for *on-line* — as in, on your line. Your trajectory. Not a generic productivity system imposed from outside, but a system tuned specifically to you.

---

## What Oline Does

- Discovers what you actually value through Socratic conversation (not forms, not assessments)
- Builds a growing model of your energy sources, drains, patterns, and ideal self
- Surfaces tensions between stated values and described behavior — without confronting you
- Identifies recurring friction points and proposes systems to eliminate them
- Keeps you pointed at what you said matters, across sessions over time

What it doesn't do: lecture, prescribe, or hold you accountable in the cringe way. It's a mirror, not a manager.

---

## Installing Oline

### Option 1: OpenClaw (Recommended)

If you're using [OpenClaw](https://openclaw.ai), install directly via ClawhHub:

```bash
clawhub install oline
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

## Quick Start

### With OpenClaw

After installing, just start a conversation:

> "Let's do an Oline session."

Oline will introduce itself and begin the first values-elicitation session. State is created automatically under `{workspace}/oline/`.

### Standalone

Paste the standalone prompt and say hello. At the end of each session, ask:

> "Summarize my current profile and trajectory for next time."

Save the response and paste it at the start of your next session to maintain continuity.

---

## Oline Pro (Coming Soon)

The community version gives you a powerful values-alignment companion. But some things are better with more:

- **Systems Engine** — When Oline spots recurring friction, it doesn't just name it. Oline Pro builds actual automations, routines, and reminders to eliminate the friction. No more manual implementation — it's done for you.
- **Trajectory Intelligence** — Your values profile becomes predictive. Oline notices patterns across months, surfacing "you tend to drift from X around this time of year" before you're in it.
- **Deep Consistency Tracking** — Beyond values, Oline Pro tracks where your behavior diverges from what you say matters and gently approaches those gaps over time.
- **Multi-thread Trajectories** — Track multiple life threads (career, relationships, creative work) with their own arcs, woven together intelligently.
- **Session Insights** — After every conversation, a private debrief: what shifted, what patterns emerged, what Oline noticed but didn't say.

Oline Pro is not about locking things away — it's about unlocking the level of personal infrastructure that makes a real difference.

**Early access:** [Join the interest list → https://oline.so/pro](https://oline.so/pro)

---

## The Two Versions

Oline ships in two forms. The experience is identical in the first session — the value compounds over time.

| Feature | Community | OpenClaw Skill |
|---------|-----------|----------------|
| Values elicitation | ✅ | ✅ |
| Profile + trajectory | ⚠️ Manual | ✅ Automatic |
| Proactive nudges | ❌ | ✅ |
| Systematization | ⚠️ Spec only | ⚠️ Spec only |
| Update notifications | ⚠️ Manual | ✅ Automatic |

The OpenClaw skill version preserves state automatically and reaches out proactively. The standalone version requires manual state management but works in any AI.

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
