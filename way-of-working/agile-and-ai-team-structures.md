# Agile and AI-Native Team Structures

Working notes on how Agile principles need to bend (or break) for teams where AI agents are first-class participants, not tools.

## The Pressure on Classical Agile

Agile's core assumptions — stable cross-functional teams, time-boxed sprints, story-pointed backlogs — were designed for a world where **execution was the bottleneck**. With capable AI agents, execution is cheap and the bottleneck moves to:

- **Intent clarity** — what exactly are we building, and why?
- **Quality and validation** — can we trust what the agent produced?
- **Coordination** — many small workstreams instead of a few large ones.

Sprints and backlogs solve the wrong problem when intent and validation are the constraints.

## Transformational Principles

Recurring themes from the source notes:

1. **Outcome boxes, not time boxes.** Replace sprints with bounded Jobs that end when the outcome is achieved.
2. **Specialty over title.** Anchor accountability to what someone is uniquely good at, not their HR role.
3. **AI agents are crew, not tools.** Plan their participation explicitly — what they're trusted with, what they aren't.
4. **Shrink the team, multiply the teams.** Small temporary crews scale better than large stable ones because they avoid coordination overhead.
5. **Make intent durable.** Specs, briefs, and steering documents become the org's memory. (See [[sdd-overview]].)
6. **Coordinate often, ceremoniously rarely.** Replace standups and sprint reviews with frequent low-ceremony Check-ins and outcome-anchored Rundowns.

## Structural Implications for Scaled Teams

- **Crews instead of squads.** Composition follows the Job, not an org chart. (See [[heist-framework]].)
- **A thin guild layer** keeps Signatures aligned across crews (standards, tooling, hiring) without owning delivery.
- **Platform teams remain stable** because their "customer" is other crews — they need long-running ownership of shared infrastructure.
- **Leadership shifts from assigning work to defining Jobs and boundaries.** The same Always/Ask/Never logic from [[sdd-roles-and-boundaries]] applies at the org level: leadership says what crews must always do, must check first, and must never do.

## Open Questions

- How do you do **performance reviews** when people move between crews every few weeks? (Likely: peer reviews per Job, aggregated by guild.)
- How do you build **deep expertise** when nothing is permanent? (Likely: Signatures + guilds carry the long-term thread.)
- How does **agent attribution** work when half the work was done by an agent under a human's review? (Open.)

## Key Takeaways

- Classical Agile optimizes the wrong constraint when execution is cheap.
- The shape that emerges is **small, temporary, outcome-bounded crews** with stable guilds and platform teams underneath.
- Boundary frameworks (Always/Ask/Never) scale from spec-level to org-level.
- The hardest unsolved problems are people-system problems (reviews, expertise, attribution), not technical ones.

## Source Document

- ![[ai-and-the-future-of-agile-report.docx]] — Analysis report this article draws from

## Related

- [[heist-framework]] — The concrete crew model these principles point to
- [[rally-model-retrospective]] — Earlier attempt at the same problem
- [[from-hierarchy-to-intelligence|From Hierarchy to Intelligence]] — Block's complementary org-level thesis
- [[sdd-roles-and-boundaries]] — Boundary framework reused at the team scale
