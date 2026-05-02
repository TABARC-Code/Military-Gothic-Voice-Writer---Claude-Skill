# military-gothic-voice

**A Claude skill system for generating and revising military gothic prose.**

Built by [TABARC-Code](https://github.com/TABARC-Code).

---

## What this is

A structured Claude skill package — one master skill, seven sub-skills, four reference files — that applies a specific prose voice to any fiction you feed it. The voice is military gothic: close-third perspective, aftermath-driven interiority, maximum dialogue subtext, physical consequences that carry moral weight. Dark, precise, and formally controlled without tipping into purple.

The techniques are derived from forensic analysis of novels spanning three settings. Worth saying plainly because a lot of "style guides" are vibes dressed up as rules. This one isn't. Every rule traces back to an observed pattern in the source texts, and every example is quoted directly from them.

It works across any genre. The setting terminology changes. The core techniques don't.

---

## What it actually does

**Generation:** give it a scene type and it configures the right sub-skill stack, drafts the prose, audits the thematic embedding, and runs a style gate before returning. It won't hand back prose with unchecked violations. That's the deal.

**Revision:** paste existing prose and it runs a four-layer diagnostic — structural, voice, sentence mechanics, vocabulary — classifies every violation by type and severity, flags what to preserve, applies corrections in the right order, and returns the passage with a note on what's most likely to go wrong next draft.

**Diagnosis:** same as revision but without the corrections. Useful if you want to understand what's broken before deciding how to fix it.

---

## Installation

Upload the zip to Claude.ai as a skill package. The entry point is `SKILL.md` — the only file Claude invokes directly. Everything else runs internally.

For original fiction or settings outside the four known registers (Dark warrioirs/Chaos style, Space Marines, Inquisition style groups/political fighting, Grim dark Fantasy Empire), the system will ask five questions to build a setting brief before generating anything. Answer them and it calibrates correctly. Skip them and it invents terminology, which is worse than useless.

Just answer them...
---

## Package structure

```
military-gothic-voice/
├── SKILL.md                           — master skill; only entry point
├── README.md                          — this file
│
├── references/
│   ├── style-checklist.md             — final gate run before every return
│   ├── violation-taxonomy.md          — every violation: wrong / right / correction
│   ├── setting-registers.md           — four confirmed vocabulary registers
│   └── activation-prompts.md          — tested invocation patterns
│
└── sub-skills/
    ├── mgv-sentence-architecture.md   — rhythm, six modes, paragraph pulse
    ├── mgv-vocabulary-fingerprints.md — clusters, qualifiers, narrator/dialogue gap
    ├── mgv-perspective-interiority.md — FID, distance, self-observation, interiority loop
    ├── mgv-dialogue-subtext.md        — five subtext rules, attribution, exchange rhythm
    ├── mgv-world-building.md          — setting terminology, environment, conflict
    ├── mgv-thematic-engine.md         — four themes, motivational architecture
    └── mgv-manuscript-diagnosis.md    — four-layer diagnosis and revision pipeline
```

---

## The three things driving every decision

**Writing from inside aftermath.** Characters aren't experiencing events — they're surviving them, carrying everything that already happened into every present moment. The past isn't behind them. It's *in* them.

**The universe is indifferent; the individual isn't.** Someone always still cares. That tension is what keeps the bleakness from tipping into nihilism. Characters keep going for reasons they can barely articulate. That's the point.

**The body is a moral register.** Physical states — augmentation, decay, damage, pain — are never merely descriptive. They externalise interior moral and spiritual conditions. The body is always a text to be read.

If those three things make sense, most of the rules under them make sense immediately. If they don't, the rules will seem arbitrary. Fair enough.

---

## How to invoke it

The simplest thing that works:

> *Write a scene in which a character who has lost the thing that gave their actions meaning continues to act anyway. They do not explain why. The setting is [X]. The action is [Y].*

The most important thing to specify is what the character won't say. Every significant scene in this voice has a silence at its centre. Name that silence and the system builds around it correctly.

Full invocation examples — including the chapter-opening prompt, the political dialogue prompt, and the diagnosis prompt — are in `references/activation-prompts.md`.

---

## What it won't do

It won't produce hope-forward prose. It won't write characters who resolve their crises through inspiration or renewed belief. It won't zoom out above the action. It won't let characters articulate their own themes aloud. It won't use an em dash for dramatic emphasis.

If those are things you want, this is the wrong tool.

---

## Version history

| Version | Changes |
|---|---|
| 1.2.0 | Author field added to SKILL.md frontmatter; README and GitHub description added |
| 1.1.0 | Bidirectional backlinks made fully specific — each connection documents what data flows, what the receiver does with it, and what the caller does with the return |
| 1.0.0 | Initial build from my forensic corpus analysis |

---

## Author

**TABARC-Code** — [github.com/TABARC-Code](https://github.com/TABARC-Code)

---

## Licence

MIT. Use it, modify it, break it in interesting ways. Credit appreciated but not required.
