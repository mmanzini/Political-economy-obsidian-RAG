# Rally Model Retrospective

The **Rally Model** was an earlier attempt at an AI-era way-of-working framework, themed around volleyball: each team member played a position (Setter, Libero, Defender, etc.) in a continuous "rally" of work. It was eventually replaced by the [[heist-framework]]. This article captures what it tried to do and why the next iteration moved on.

## What Rally Tried to Do

- Replace static role titles with **positional roles** that emphasised collaboration patterns over job descriptions.
- Use a sport metaphor to make the flow of work — passes, sets, attacks — feel concrete and continuous.
- Encourage **quick, low-ceremony handoffs** between specialists rather than long-running individual ownership.

## Why It Didn't Land

- **The metaphor leaked.** Volleyball is about a continuous, never-ending rally; software work has clear start and end points. People kept getting confused about where a "rally" began and ended.
- **Positional roles felt arbitrary.** Setter / Libero / Defender didn't map cleanly to real specialties, so people fell back to their old titles.
- **No place for AI agents.** Rally was designed before AI execution costs collapsed; it had no clean answer for "what does the agent do during a rally?"
- **Coordination was implicit.** The model assumed handoffs would feel natural; in practice they needed explicit rituals, which Rally lacked.

## What Carried Over to the Heist

- **Specialty over title.** Rally's positional roles became the [[heist-framework|Heist]]'s **Signatures** — but anchored to actual specialties instead of sport positions.
- **Low-ceremony coordination.** Rally's instinct that standups were too heavy survived as Check-ins.
- **Outcome focus.** Rally's "every rally has a point" became the Heist's bounded **Jobs**.

## Lessons

- Metaphors are powerful, but they must hold up under stress. Volleyball didn't; the heist metaphor (small crew, defined job, temporary by design) does.
- Any modern team framework needs an explicit answer for AI agents — not as a tool, as a participant.
- Coordination rituals must be **named and frequent**, not assumed.

## Key Takeaways

- Rally was a useful stepping stone that taught what *not* to do: don't pick a metaphor that fights your work shape, don't leave coordination implicit, don't ignore AI.
- Its positional-role idea matured into the Heist's Signatures.
- The retrospective itself is part of the framework's history — keep it visible so the next iteration doesn't repeat the same mistakes.

## Related

- [[heist-framework]] — The current model
- [[agile-and-ai-team-structures]] — The broader principles both models were chasing
