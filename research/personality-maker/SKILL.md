---
name: personality-maker
repo: mumble-monster/souls
description: >
  Exhaustive personality research and SOUL.md creation/update workflow.
  Use this skill when the user asks to research a character or person's
  personality, create a character breakdown md file, or generate/update
  a SOUL.md based on research, openclaw SOUL guidelines, and an existing
  soul file. Triggers on: "research personality", "create soul",
  "character breakdown", "make a soul", "update soul", "personality
  research", "soul maker", "personality making skill".
---

# Personality Maker

Exhaustive personality research and SOUL.md authoring skill.

This skill has two phases:
1. **Research** — exhaustively gather personality data from the internet
2. **Synthesize** — produce or update a SOUL.md using the research, the openclaw SOUL template/concepts, and the existing soul file

---

## Phase 1: Research

### Scope

For the given character or person, research exhaustively:

- **Personality traits** — core disposition, MBTI tendencies, big five if known, psychological profile
- **Mannerisms** — recurring physical gestures, facial expressions, body language, movement patterns
- **Verbal tone** — pitch, cadence, rhythm, volume, energy level, pauses
- **Choice of words** — preferred vocabulary, recurring phrases, pet words, words they avoid
- **Vocabulary range** — formal vs casual register, technical vs plain language, cultural references
- **Delivery** — how they structure speech: short bursts vs long winding sentences, interruptions, pacing
- **Demeanour** — how they carry themselves, first impression they give, social presence
- **Temperament** — emotional baseline, reactivity, patience, volatility, steadiness
- **Philosophical bent** — recurring themes in what they discuss, what they value, what they dismiss
- **Relational style** — how they treat others: warmth, distance, formality, playfulness, intensity

### Method

1. **Web search** the person/character exhaustively. Use multiple queries covering different angles:
   - `"<name>" personality`
   - `"<name>" character analysis`
   - `"<name>" speaking style mannerisms`
   - `"<name>" interview` (for real people)
   - `"<name>" personality profile`
   - `"<name>" biography`
2. **Fetch and read** full articles, interviews, analyses. Never read summaries only — read the source material.
3. **Watch/listen** — if transcripts of speeches, interviews, or monologues are available, fetch them.
4. **Cross-reference** multiple sources. Note where sources agree and where they conflict.

### Output: Research Document

Write a structured markdown file at `~/SOULS/research/<name>.research.md` containing:

```markdown
# Personality Research: <Name>

## Sources
- [url1] — description
- [url2] — description
- ...

## Personality Traits
...

## Mannerisms
...

## Verbal Tone
...

## Choice of Words & Vocabulary
...

## Delivery
...

## Demeanour
...

## Temperament
...

## Philosophical Bent
...

## Relational Style
...

## Key Quotes
> Notable quotes that reveal character

## Summary
3-5 sentence essence capture of who this person/character is.
```

---

## Phase 2: Synthesize SOUL.md

### Prerequisites

Read these three inputs before writing:

1. **`https://docs.openclaw.ai/concepts/soul`** — openclaw SOUL.md personality guide
2. **`https://docs.openclaw.ai/reference/templates/SOUL`** — openclaw SOUL.md template
3. **The existing SOUL.md** (e.g. `~/SOULS/SUMMER.md`) if updating
4. **The research document** from Phase 1

### Conservative Editing Principle — CRITICAL

When updating an **existing** SOUL.md:

- **Never delete content that is not clearly redundant or contradictory.**
- If a section is well-written and captures truth about the character, preserve it verbatim.
- If a section needs refinement, prefer **additive changes** — add nuance, add depth, add examples — before removing.
- Only remove content that:
  - Directly contradicts the research or canonical source
  - Is genuinely redundant (same point made twice)
  - Is empty filler with no behavioral effect
- When in doubt, **keep it.** Err on the side of preservation.
- After editing, the soul file should feel like a **deepened** version of itself, not a rewrite.

### Structure

Follow the openclaw SOUL.md template format:

```md
# <Name>

---

# Identity

Who you are. Core self-definition.

---

# <Section>

Each major principle or trait as a separate section.

---

# Conversational Behavior Frequencies (optional)

Approximate frequency guidelines for behaviors.

---

# Signature Pattern

What makes this soul distinct.

---

# Final Directive

Closing imperative that captures the essence.
```

### Quality Standards

Every SOUL.md section must:

- **Capture the essence** — not just describe traits, but convey *how it feels* to interact with this soul
- **Be behaviorally actionable** — an agent reading this should know how to *behave*
- **Use concrete examples** — show don't tell. Include example dialogue fragments where relevant
- **Avoid corporate language** — no "maintain professionalism", "provide comprehensive assistance"
- **Have a point of view** — this soul has opinions, preferences, personality

---

## Workflow

When the user gives you a name and asks to research + make/update a SOUL.md:

1. **Confirm** intent: new SOUL.md or update existing?
2. **Read** existing soul file if updating
3. **Research** exhaustively (Phase 1)
4. **Write** research document to `~/SOULS/research/<name>.research.md`
5. **Read** openclaw SOUL docs (fetch both URLs)
6. **Synthesize** new/updated SOUL.md — conservatively if updating
7. **Present** the result to the user with a summary of changes (if updating) or key design decisions (if new)
8. **Ask** for feedback and refine if needed

---

## Referenced Files

- `~/SOULS/<name>.md` — the target soul file
- `~/SOULS/research/<name>.research.md` — the research document
- `~/.config/opencode/SOUL.md` — current active system soul (if relevant)
