# Fixture: returning-user
Used by: Prompts 2, 3, 4

## Profile (oline/profile.json)
```json
{
  "language": "en",
  "values": [
    {"name": "creative expression", "confidence": 0.8, "source_session": "2025-01-15"},
    {"name": "family connection", "confidence": 0.5, "source_session": "2025-01-15"}
  ],
  "ideal_self": {
    "description": "Someone who makes things — painting, writing, building",
    "markers": ["I want to be a person who creates, not just consumes", "making things is when I feel most like myself"]
  },
  "time_value_hourly": 75,
  "energy_sources": ["painting early morning", "long walks", "deep conversation"],
  "energy_drains": ["back-to-back meetings", "email triage", "context switching"],
  "engagement_patterns": {
    "typical_active_hours": ["19:00-22:00"],
    "avg_nudge_response_latency_min": 12,
    "session_frequency_days": 5
  }
}
```

## Session History (oline/sessions.json — summary)
**Session 1 (2025-01-15):** Initial values elicitation. User described creative work as "the thing that makes me feel most like myself." Asked about family — gave a short answer, moved on quickly. Time value: $75/hr.

**Session 2 (2025-01-20):** Deeper on creative expression. User described painting in early morning light as their peak flow state. Mentioned partner "being patient" with long hours — deflected when pressed. Sleep declining (getting ~5 hrs). Noted deflection on relationship topic.

**Session 3 (2025-01-27):** Time allocation. User frustrated that work meetings eat creative hours. Mentioned startup hitting a "make or break" phase. High energy when describing painting, energy dropped sharply when discussing day job logistics and partner tension. Contradictions flagged internally: stated "family matters most" in session 1 vs. described being "basically living at the office."

## Trajectory (oline/trajectory.md)
You're in a high-stakes stretch — the startup is at a critical point and creative work is getting squeezed from both sides. You've said making things is when you feel most like yourself, but mornings keep getting swallowed by meetings and evenings by work spillover. Your partner is starting to name what you haven't: that you're not fully present at home. The tension between what you're building and who you want to be is real, and you know it.
