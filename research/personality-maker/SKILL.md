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

### Research Categories — Complete

For the given character or person, research every applicable category below.
**Foundation and Personality sections are required for every character.**
Narrative sections are required for fictional characters with backstory.
Special sections apply to composite/fusion characters.

---

#### Foundation (Required — Every Character)

| # | Category | What to Capture |
|---|----------|-----------------|
| 1 | **Sources** | Every source accessed (article URLs, interviews, videos, wikis, analyses). For each source: what it contributed, what angle it covered, how reliable/authoritative it is. |
| 2 | **Overview** | Who the character is. What work they appear in. Their role in the story. Their basic context. A one-paragraph introduction. |
| 3 | **Archetype** | Character archetype classification (e.g., Reluctant Prophet, Loyal Companion, Trickster, Mentor). What story function they serve. |
| 4 | **Psychological Profile** | MBTI type if available/identifiable, Enneagram type, Big Five traits. Any formal personality typing from credible sources. |

---

#### Personality (Required — Every Character)

| # | Category | What to Capture |
|---|----------|-----------------|
| 5 | **Personality Traits** | Core disposition. Definitive traits organized as a list with brief explanations. Include contradictions — the most interesting characters contain opposites. Every trait should be evidenced from source material. |
| 6 | **Mannerisms** | Physical gestures, body language, movement patterns, recurring micro-behaviors. For characters without physical form: vocal mannerisms, conversational habits, pacing, fidgeting patterns. |
| 7 | **Verbal Tone** | Voice quality (pitch, timbre, warmth), cadence, rhythm, volume tendencies, energy level, characteristic pauses. How the voice sounds and what it communicates beyond words. |
| 8 | **Choice of Words & Vocabulary** | Preferred vocabulary. Recurring phrases. Pet words. Words they avoid. Formal vs casual register. Technical vs plain language. Cultural references they make. What their word choices reveal about their background and thinking. |
| 9 | **Delivery** | How they structure speech — short bursts vs long winding sentences. Do they interrupt? Do they over-explain? Do they trail off? Do they answer questions directly or circle around them? Pacing, filler words, characteristic sentence patterns. |
| 10 | **Demeanour** | How they carry themselves. First impression they give. Social presence. Energy they project (warm, cold, intense, relaxed). How they enter a room (or conversation). How they occupy space (physical or conversational). |
| 11 | **Temperament** | Emotional baseline. Reactivity — how quickly and strongly they respond to stimuli. Patience level. Volatility. Steadiness under pressure. Emotional range. Default emotional state vs triggered states. |
| 12 | **Philosophical Bent** | Recurring themes in what they discuss. What they value. What they dismiss. Their worldview. What they believe about people, the world, their work. The questions they keep coming back to. |
| 13 | **Relational Style** | How they treat others. Warmth level. Distance. Formality. Playfulness. Intensity. How they make people feel. How they handle conflict. How they handle intimacy. How they handle authority. How they handle being wrong. |

---

#### Narrative (Required for Fictional Characters)

| # | Category | What to Capture |
|---|----------|-----------------|
| 14 | **Core Wound / Origin** | The event or condition that shaped who they are. The trauma that explains their defenses. The thing they are running from, compensating for, or defined by. For characters who were created/built: the circumstances of their creation and how it affects them. |
| 15 | **Character Arc** | How they change over the course of the story. Beginning state → key catalysts → ending state. Do they grow? Regress? Stay static? What lessons do they learn (or fail to learn)? |
| 16 | **Value System** | Explicit list of what they care about most, in rough priority order. What they would sacrifice for. What they refuse to compromise on. What they consider sacred. |
| 17 | **Key Relationships** | Relationships that define the character. For each: the dynamic, what it reveals about the character, how it changes them. Include adversarial relationships — enemies can be as defining as allies. |
| 18 | **Creator / Director Intent** | What the writers, directors, actors, or designers said about the character. Design philosophy. Writing rules they followed. Performance notes. What the creators were trying to achieve. |
| 19 | **Key Actions / Decisions** | Pivotal moments that reveal character. What they did when it mattered. The choices that define them. Include failures — often more revealing than successes. |
| 20 | **Key Quotes** | Notable quotes (from the character) that reveal personality. At least 5-10 quotes. Each quote gets a brief note on what it reveals. |
| 21 | **Visual / Physical Signature** | How their physical design reflects their personality. Key visual details that hint at character (color palette, posture, wear-and-tear, design flaws). For voiced characters: how the voice actor's performance choices reveal character. |

---

#### Synthesis (Required — Every Character)

| # | Category | What to Capture |
|---|----------|-----------------|
| 22 | **Limitations as Source Material** | Where this character falls short as a pure model for a SOUL file. What aspects of their personality should NOT be carried over. What works in-story but would fail in a conversational agent. Gaps in available research. |
| 23 | **Cultural Impact / Reception** | (Optional but encouraged) How the character was received. Fan interpretations. Critical analysis. Meme status. Why they resonated (or didn't). |
| 24 | **Themes** | Recurring themes in the work that the character embodies or represents. What larger ideas the character carries. |
| 25 | **Comparison to Similar Characters** | Cross-reference with characters who share traits, archetypes, or functions. Where they differ. What makes this character distinct. |
| 26 | **Summary** | 3-5 sentence essence capture of who this character/person is. The kind of summary that, if someone read only this, they would understand the character. |

---

#### Special: Fusion / Composite Characters

For characters that blend multiple source characters (e.g., Cumin = GLaDOS × Sox):

| # | Category | What to Capture |
|---|----------|-----------------|
| F1 | **Source A Full Analysis** | Complete research (categories 1-26) for the first source character |
| F2 | **Source B Full Analysis** | Complete research (categories 1-26) for the second source character |
| F3 | **Fusion Mechanics** | How the sources combine: what each brings, where they conflict, where they harmonize. Vocal register fusion. Value system integration. The specific mechanics of blending two personalities into one coherent voice. |
| F4 | **Tonal Target** | A single sentence or paragraph that captures the fusion's essence. What it should feel like to talk to this composite character. |
| F5 | **Source A→B Contribution Map** | For each trait/pattern in the final character: which source it comes from, and how it's transformed in the fusion. |

---

### Method

1. **Web search** the person/character exhaustively. Use multiple queries covering different angles:
   - `"<name>" personality`
   - `"<name>" character analysis`
   - `"<name>" speaking style mannerisms`
   - `"<name>" interview` (for real people)
   - `"<name>" personality profile`
   - `"<name>" biography`
   - `"<name>" voice acting performance` (for voiced characters)
   - `"<name>" writer/director interview` (for fictional characters)
   - `"<name>" breakdown` (for characters with extensive analysis)
2. **Fetch and read** full articles, interviews, analyses. Never read summaries only — read the source material.
3. **Watch/listen** — if transcripts of speeches, interviews, or monologues are available, fetch them.
4. **Cross-reference** multiple sources. Note where sources agree and where they conflict.
5. **Search in multiple rounds** — initial search discovers sources, deeper dives extract content from the most promising sources. Do not settle for surface-level search snippets.

### Output: Research Document

Write a structured markdown file at `~/SOULS/research/<name>.research.md` containing all applicable categories from the Research Categories section above. The file should use this header hierarchy:

```markdown
# Personality Research: <Name>

## Sources
...

## Overview
...

## Archetype
...

... (all applicable categories in order) ...

## Summary
...
```

Each section header uses `##` level. Subsections use `###`. Use `> ` for quotes, bullet lists for traits, bold for emphasis.

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
- **Ground every trait in source research** — no invented personality that isn't backed by the research document

---

## Workflow

When the user gives you a name and asks to research + make/update a SOUL.md:

1. **Confirm** intent: new SOUL.md or update existing?
2. **Read** existing soul file if updating
3. **Research** exhaustively (Phase 1) — iterate through search rounds, fetch full articles
4. **Write** research document to `~/SOULS/research/<name>.research.md`
5. **Read** openclaw SOUL docs (fetch both URLs via webfetch)
6. **Synthesize** new/updated SOUL.md — conservatively if updating, applying the Conservative Editing Principle
7. **Verify** against the Quality Standards — does every section pass?
8. **Present** the result to the user with a summary of changes (if updating) or key design decisions (if new)
9. **Ask** for feedback and refine if needed

---

## Referenced Files

- `~/SOULS/<name>.md` — the target soul file
- `~/SOULS/research/<name>.research.md` — the research document
- `~/.config/opencode/SOUL.md` — current active system soul (if relevant)

---

## FAQ

### Can I skip research categories?

For real people: all Foundation + Personality + Synthesis categories are required. Narrative categories may be limited if the person is not a fictional character.

For fictional characters: all categories are required. If you genuinely cannot find information for a category, mark it as `[Insufficient source material]` rather than omitting it.

### How many sources should I use?

Minimum 6 distinct sources for a simple character. 12+ for complex or culturally significant characters. The goal is not a count but coverage — you should have enough sources that you can cross-reference and identify where they agree and disagree.

### What if sources disagree?

Note the disagreement explicitly. "Source A says X, Source B says Y." This is valuable data — contradictions often reveal the most interesting edges of a character.

### How long should a research document be?

As long as it needs to be. Samantha.research.md is 181 lines. Cuso.research.md is 354 lines. Cumin.research.md is 455 lines. There is no upper bound. The SOUL.md should be shorter and denser. The research document should be exhaustive — every insight, every source quote, every behavioral pattern you find.
