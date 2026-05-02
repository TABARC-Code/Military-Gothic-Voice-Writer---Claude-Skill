---
name: military-gothic-voice
version: 2.0.0
author: TABARC-Code
title: Military Gothic Voice — Complete Prose System
role: orchestrator
user-invocable: true
model: sonnet
effort: high
description: >
  Applies a complete military gothic prose voice to any fiction across any setting. Use when
  the user wants: grimdark voice, dark military fiction, aftermath-driven interiority, close-third
  POV with self-observing characters, maximum dialogue subtext, environment as structural mirror,
  body-as-moral-register, duty-without-faith themes, formal gravity paired with raw physical
  specificity. Triggers on: "grimdark voice," "dark military fiction," "psychological interiority,"
  "close third POV," "write in a dark precise style," "military gothic," "write like serious
  fantasy fiction," or any request to generate or revise prose toward this register. Covers
  generation, revision, and diagnosis modes across any genre or setting.
---

# Military Gothic Voice — Complete Prose System

**Author:** TABARC-Code

---

## THREE FOUNDATIONAL TRUTHS

These are the structural laws of this voice. Every technique below exists to serve them.

**Truth 1 — Writing from inside aftermath.** Characters are not experiencing events — they are *surviving* them, carrying everything that already happened into every present moment. The past is not behind characters. It is *in* them, pressing outward.

**Truth 2 — The universe is indifferent; the individual is not.** Characters care with painful intensity inside a cosmos that does not reciprocate. Someone always still cares. This tension is what keeps the bleakness from nihilism.

**Truth 3 — The body as moral register.** Physical states — decay, damage, pain, augmentation — are never merely descriptive. They externalise interior moral and spiritual conditions. The body is always a text to be read.

---

## MODE DETECTION — FIRST STEP

| Mode | Signal | First action |
|---|---|---|
| **Generation** | User wants new prose | Configure sub-skill stack from routing table |
| **Revision** | User has existing prose | Run Manuscript Diagnosis section first |
| **Diagnosis** | User wants to know what's wrong | Run Manuscript Diagnosis section only |

For revision and diagnosis: always run the Manuscript Diagnosis section first. Revision by inference misses structural violations that require sequenced correction.

---

## SETTING CHECK — BEFORE GENERATION

**Known settings** (vocabulary registers in the Setting Registers section below):
- Warhammer 40,000: Death Guard/Chaos; Space Marine (loyal)/Astra Militarum; Inquisition/political
- Warhammer Fantasy Empire: Military/campaign; Political/court

**Unknown or original settings:** ask the user for setting name, POV character name, faction, opponent faction (if conflict present), key world-specific terms with physical descriptions. Maximum five questions. Build a setting brief and apply it during world-building and vocabulary calibration before generation.

Do not invent terminology. Do not proceed without a setting brief for unknown settings.

---

## TASK ROUTING TABLE

| Task | Primary section | Secondary |
|---|---|---|
| Draft action sequence | Sentence Architecture | World-Building |
| Draft introspective passage | Perspective & Interiority | Vocabulary Fingerprints |
| Draft dialogue scene | Dialogue & Subtext | Perspective & Interiority |
| Draft chapter opening | Sentence Architecture | Perspective & Interiority |
| Build environment | World-Building | Vocabulary Fingerprints |
| Embed theme | Thematic Engine | Vocabulary Fingerprints |
| Vocabulary audit | Vocabulary Fingerprints | Perspective & Interiority |
| Full scene generation | All sections in sequence | — |
| Diagnose existing prose | Manuscript Diagnosis | — |
| Revise existing prose | Manuscript Diagnosis | Relevant sections per findings |

---

## GENERATION PROCEDURE

Execute in strict order. Do not combine steps.

**Step 1 — Setting check**
Confirm setting brief is loaded. If unknown: collect brief (max five questions).

**Step 2 — Mode identification**
Identify dominant sentence mode: action / introspection / tactical / revelation. Mixed scenes: identify dominant and secondary.

**Step 3 — Theme identification**
Identify active theme from the four (see Thematic Engine section). One primary, one optional secondary.

**Step 4 — Draft**
Execute using the Sentence Architecture section first, then Perspective & Interiority, then Dialogue & Subtext (if present), then World-Building (if present), then Thematic Engine, then Vocabulary Fingerprints.

**Step 5 — Theme audit**
After draft: is the theme in action and consequence, or stated directly? Does any character speak their theme aloud? Does any paragraph resolve through hope or faith without qualification? If yes to any: revise before proceeding.

**Step 6 — Style gate**
Run the Style Checklist section (below). Any unchecked box is a revision pass.

**Step 7 — Output**
Return: setting brief status, active sections used, drafted prose, post-draft note (one risk, one next beat).

---

## REVISION PROCEDURE

**Step 1 — Diagnosis**
Run the Manuscript Diagnosis section fully. Do not touch prose before this completes.

**Step 2 — Preserve**
Identify and protect passages flagged as working. Revision works around these, not through them.

**Step 3 — Layered correction**
Structural violations first → voice violations → sentence mechanics → vocabulary. Do not apply surface corrections to prose with unresolved structural violations.

**Step 4 — Style gate**
Run the Style Checklist section.

---

## ABSOLUTE PROHIBITIONS

Any of these present means stop and revise before returning:

- Omniscient narration beyond POV character's direct sensory range
- Ellipsis for emotional effect in narration
- Em dash for dramatic pause, trailing effect, or emotional intensification
- Nature directly reflecting character's feelings (pathetic fallacy)
- Characters articulating their own themes aloud
- Hope or faith stated without immediate qualification
- "he felt X" without a following observation that complicates X
- Adverb-modified dialogue attribution
- Philosophical vocabulary in dialogue (void, mortal, flesh, soul, shadow, ruin, ash, persist, endure, remain)
- Action beats that explain what they mean
- Three consecutive paragraphs with identical pulse shape
- Flashback sections over one paragraph in length

---

---

# SUB-SKILL: SENTENCE ARCHITECTURE AND PARAGRAPH PULSE

Controls cadence, sentence length, paragraph structure, and mode calibration.

## Sequential procedure

1. Identify mode from the six modes below; if scene involves rout/chaos, use rout variant; if writing environmental biography, use historical mode
2. Apply mode-specific sentence length constraints
3. Structure paragraphs using four-stage pulse (introspective/narrative mode) or Entry-Cut only (action mode)
4. Apply accumulate-then-strike rhythm at sentence level
5. Integrate action and atmosphere via participial stacks — never separate sentences
6. Apply em dash rule (two permitted uses only)
7. **Physical anchor check (introspective mode):** each introspective paragraph must contain at least one concrete noun — body part, surface, object, sound, smell. If absent: add one before proceeding.
8. **Single-line paragraph check:** confirm any single-line paragraph serves one of three structural functions (see below). If used for emphasis only: restructure.
9. Return: mode identified, calibration applied, physical anchor confirmed, single-line function declared, prose, mode-shift notes

## The six modes

### Introspective / reflective mode
- **Length:** 20–45 words
- **Structure:** participial phrases, subordinate clauses, em-dash asides permitted
- **Function:** character processing experience in real time
- **Voice:** free indirect discourse throughout — no tagged thoughts
- **Qualifiers:** permitted; never the same qualifier twice within 200 words
- **Example:** *He had learned — in the long specific silence of the years after — that the waiting was its own kind of work, the kind that left no visible product and asked nothing of the hands.*

### Action mode
- **Length:** 8–18 words
- **Structure:** subject-verb dominant; objects functional, not described
- **Function:** physical events at speed
- **Voice:** pronouns replace names; no time for full identification
- **Qualifiers:** zero. Any qualifier in action mode must be removed.
- **Example:** *Skarr spun his sword round, switching to a two-handed grip. He parried it away and leapt clear.*

### Tactical observation mode
- **Length:** 15–25 words
- **Structure:** present-tense feel even in past tense; cataloguing, professional detachment
- **Function:** character assessing a situation
- **One sentence per observation; move on immediately**

### Revelation / emotional climax mode
- **Length:** 2–8 words; often fragments; often bare nouns
- **Function:** terminus — all preceding paragraphs collapse to this point
- **Deployment:** once per significant scene; never for general dramatic emphasis
- **Examples:** *Live. Survive. A place will be found.* / *Survive.* / *He moved anyway.*

### Action mode — rout variant
- **Length:** 40–70 words in a single sentence
- **Function:** loss of tactical control; the sentence length enacts the disintegration
- **Internal rhythm:** tripling ("sliding and skidding and dropping"), accumulating abandonment ("leaving weapons, leaving shields, dropping it all")
- **Deployment:** one per scene; genuine rout/overwhelm context only. Do not break into short sentences — the length IS the meaning.
- **Example:** *He turned heavily, slipping in the already-boiling mud, limping back the way he'd come, along with all the rest of them, sliding and skidding and dropping to all fours, leaving weapons, leaving shields and trophies, dropping it all, forgetting it all, just scrambling out of that inferno before the waves of pain overtook them.*

### Historical / record mode
- **Length:** 25–50 words; past-perfect dominant
- **Structure:** archival, procedural; dates, proper nouns, institutional facts
- **Function:** biography of a significant environment — reveals what it has become versus what it was
- **Voice:** narrator withdraws from POV entirely; cool, ironic gap between the record and the reality
- **Deployment:** for ships, buildings, or institutions with histories that shape their present; one per work

## The accumulate-then-strike rhythm

Build pressure; release flatly. The cut is always flat and unqualified.

**Pattern A (long-to-short):**
> He had been at the edge of this kind of decision before — not once or twice but enough times that it had its own texture, its own particular quality of silence in the chest. He had learned, in those previous moments, that the thinking was never the hard part. *Acting was. It always was.*

**Pattern B (short-to-long):**
> *Pain.* That was all that remained. Sometimes a dull, throbbing ache, distributed evenly across his body. Other times, they made it sharp and sudden. *It all depended on her mood.*

**Short-short-long variant:**
> *The humiliation of it. The raw, unbearable humiliation. That was the worst wound, far worse than any physical flesh-breaking.*

## The four-stage paragraph pulse

Use in introspective and narrative paragraphs. Over any three consecutive paragraphs, all four stages must appear across the set.

**Stage 1 — Entry:** short declarative, often fragment; establishes POV and stakes; begins the paragraph, does not set it up.

**Stage 2 — Expansion:** 2–4 sentences of building complexity; atmosphere, interior thought, setting detail — all embedded in action.

**Stage 3 — Complication:** one sentence cutting against the expansion; a doubt, a physical detail that doesn't fit, a shift in assessment.

**Stage 4 — Cut:** 3–5 words where possible; flat; no qualifier.

**Anti-mechanical rule:** Never write three consecutive paragraphs with identical pulse shape. After two full pulses: vary — end mid-expansion, open with complication, run two expansions before complicating.

**Cross-mode constraint:** When adding thematic content or emotional weight to an action passage, the addition must be at action-mode length (8–18 words). Introspective-mode sentences inserted into action passages without a structural break are a mode mismatch regardless of content quality. If the content won't compress to action-mode length: paragraph break first, then introspective sentence.

## The participial stack

Never separate action from atmosphere into distinct sentences. Atmosphere lives in the grammar of motion.

> He ran, his boots slipping in the dark corridor's filth, the voices behind him closing faster than he'd allowed for.

Three participial layers maximum. Four becomes a list.

## Chapter openings

Open at least three beats into the scene. Character in motion; setting arrives in the gaps. First sentence must contain a verb doing actual work — not being or having.

**Deferred subject identification:** Subject can be withheld for five or more paragraphs when the character's psychological state is itself the content. Use when panic, fugue, or decisive momentum under collapse would be diluted by pausing to identify who they are. The moment of naming arrives when the character regains coherence — which is itself a narrative event.

- Standard: three beats in; subject clear by paragraph two
- Extended: five to eight beats; named by paragraph three
- Extreme: five-plus paragraphs unnamed; requires genuine psychological urgency

## Single-line paragraphs — three structural functions only

1. **Crystallisation terminus:** all preceding paragraphs built toward this; the conclusion collapses the weight.
2. **Rhythm beat in counting or enumeration:** marks beats within a counting sequence; prose fills the spaces.
3. **Interruption of interior by exterior action:** physical event breaks into an introspective passage.

Never for dramatic emphasis, atmospheric intensification, or to make a sentence feel important. Maximum once every three to four pages.

## Em dash rules

**Permitted 1 — Narrator commentary within attribution:**
> *'It can be restored,' he said — not a decision, so much as an acknowledgement of what had already been decided.*

**Permitted 2 — Subordinate clarification in long introspective sentence:**
> *He had learned — in the years after the second collapse — that waiting was a skill like any other.*

**Banned:** dramatic pause; trailing effect; emotional intensification. One em dash per paragraph maximum. Introspective mode only — never in action mode sentences.

---

---

# SUB-SKILL: VOCABULARY FINGERPRINTS AND REGISTER

Controls word choice at vocabulary cluster, qualifier tic, and narrator/dialogue gap level. Applied last in the generation stack.

## Sequential procedure

1. Identify the active vocabulary cluster for this passage
2. Confirm no cluster crossover — words from a different cluster present
3. Run mandatory qualifier scan: all nine qualifiers (primary six + secondary three); check position, spacing, mode eligibility
4. Verify philosophical vocabulary is absent from all dialogue
5. Audit narrator/dialogue voice gap: confirm character speech uses character vocabulary, not narrator vocabulary
6. Return: active cluster, qualifier scan results, violations flagged, corrected prose

## Core philosophical vocabulary — narration only, never in dialogue

**Existential:** void, mortal, flesh, soul, shadow, ruin, ash, dust, remnant, vestige
**Process:** persist, endure, survive, remain, continue, sustain, maintain
**Interiority:** dull, throbbing, raw, acute, agonising, numb
**Temporal:** still, already, now, long ago, once, what remained
**Judgment:** merely, perhaps, surely, possibly, no doubt, in truth

**Absolute rule:** These words appear in narration only — never in dialogue. Remove immediately and replace with the plainest character-register equivalent.

## Primary six qualifier tics

Each must appear no more than once every 400–500 words. Overuse depletes them. **Mandatory scan before returning any prose:** locate every instance of all six, map positions, cut any appearing twice within 400 words.

**Mode restriction:** All six qualifiers are for introspective and reflective narration only. In action mode: zero qualifiers permitted.

**"merely"** — Ironic minimisation. What follows is smaller than it is. *He is merely a puppet now.*
Misuse: simple qualification without ironic load. *He was merely tired.* → cut.

**"still"** — Temporal persistence against expectation. Things continuing when they should have stopped.
*She smiled, still.* — persistence of the smile when it should have faded is the point.
Misuse: simple continuative. *He was still standing.* → restructure.

**"already"** — The past arriving too soon. Loss pre-announced.
*He felt it already, the cold.* — the cold hasn't arrived; the character feels its approach.
Misuse: simple anteriority. *She had already left.* → remove.

**"somehow"** — Acknowledgement of improbability without explanation. The miracle registered but not resolved.
*Somehow they had made it out.* — the how is not available. The fact is.
Misuse: vague causation. *He somehow found himself agreeing.* → restructure.

**"in truth"** — Narrator correcting after a character's stated belief or claim.
*He had told himself it was duty. In truth, it had been fear.*
Misuse: emphasis without correction. *In truth, it was a good plan.* → cut phrase.

**"of course"** — Weariness, irony, acceptance. Character accepting what had been resisted.
*Of course he's slower.* — the moment of accepting what had been avoided.
Misuse: enthusiasm or confirmation. *Of course it worked!* → remove.

## Secondary qualifiers — lower weight, same mode restriction

**"probably"** — casual hedge and wry detachment marker. More frequent than primary six; still narration only, not action mode. Trailing "probably" at sentence end signals ironic approximation.
> *"which is probably for the best"* / *"That counts as forgiveness, probably."*

**"most likely"** — archival equivalent of "probably." Historical mode and formal characters.
> *"Some wasting Gift in his vocal cords, most likely."*

**"no doubt"** — inevitable consequence noted without enthusiasm.
> *"No doubt he'd been scanned."*

## The "something like" construction

Characters approximating an emotion or state they cannot fully classify:
> *Something like a uniform still clings to his hefty frame.*
> *He felt something like satisfaction.*

Signals alienation from interiority. Characteristic of Death Guard, Iron Hands, and any character for whom emotional classification has become irrelevant. Not a weakness — the approximation IS the characterisation.

## Vocabulary cluster consistency

Maintain the active cluster throughout a passage. Cluster crossover generates tonal inconsistency.

**Duty-without-faith cluster:**
*obligation, purpose, task, service, function, endure, serve, call, sworn, honoured*
Characters doing what they should even when they no longer believe in why.
Forbidden: "hope," "faith" — unless immediately undercut in the same or next sentence.

**Decay-and-persistence cluster:**
*rot, crust, patina, fused, coated, encrusted, absorbed, consumed, thickened, patient, gradual, eventual*
Long-running corruption, transformation, or physical decay. The rot is neutral, never evil.
Architecture in this cluster extrudes and grows — never built. Setting is the moral condition of inhabitants made spatial.

**Identity-under-erasure cluster:**
*once, before, then, no longer, had been, the man he was, what remained, the thing he had become*
Any scene involving transformation, loss of self, or measuring against a previous version.
Key word: *once.* Characters defined against what they were.

**Political-threat cluster:**
*careful, scheme, position, advantage, rival, enemies, power, game, rise, control*
Political scenes, institutional hierarchy, tactical positioning between factions.
Effect on prose: sentences shorten, adjectives thin out, information density increases.

## Narrator/dialogue voice gap — non-negotiable

Characters speak differently from the narrator.

> Narrator: *The truth of it was slow to arrive, painful in proportion to how long it had been resisted.*
> Character: *"What happened?"*

A character who speaks with narrative sophistication has broken the gap. Strip philosophical vocabulary; replace with the plainest possible statement.

**Vocabulary audit — every line of dialogue:**
1. Take the line
2. Locate any word from the philosophical vocabulary lists
3. If present: rewrite in the character's register
4. Characters sound like people. Narrators sound like the voice of history with a personal wound.

**Confirmed character registers:**
- Measured, question-based: *"What happened?" / "Run the numbers."*
- Terse, contemptuous: *"Not good enough." / "Get it done."*
- Epigrammatic: *"This year, then, I hope you will listen."*
- Arch, informative: *"I'll not sweeten this for you."*
- Cold, functional: *"They are mistaken. Such error is fatal."*

Establish a character's register in their first exchange and maintain it. Register shift is a deliberate signal — use intentionally or not at all.

---

---

# SUB-SKILL: PERSPECTIVE AND INTERIORITY

Controls how close the narration sits to the character's consciousness, how thoughts exist without being tagged, how the past intrudes on the present.

## Sequential procedure

1. Identify narrative distance: close third (default) or mid third
2. Confirm free indirect discourse is active — no hard tags
3. After any significant emotional beat: insert one self-observation sentence (2–6 words)
4. Check for temporal intrusion triggers; apply if present — max one paragraph, immediate return to present
5. **Interiority loop check:** does the character's thinking move in a clean line from question to qualified answer? If yes: introduce a loop, self-contradiction, or distrusted inference before the resolution. Clean-line interiority is always too smooth.
6. Verify no distance shift mid-scene without narrative purpose
7. Return: distance mode, FID status with example, self-observation present, temporal intrusion check, interiority loop present, prose

## Free indirect discourse

Interiority delivered without tagging it as thought. The narrator thinks *for* the character. No "he thought," "she noticed," "he realised." The thought exists in narration as if it were fact.

**Signal FID is active:** tense slippage from past observation to present assessment within the same passage.

> *He glanced at one of the buried servitor faces. It has no eyes, no nose, just an open mouth crammed full of electric strobe lines. Its lower lip spasms.*

Note: *glanced* (past) → *has, spasms* (present). The narrator has entered the character's present without announcement.

**Hard tags that break FID — remove:**
- "he thought" / "he realised" / "she noticed" — closes the thought, pulls narrator outside
- "she felt" as a state report without physical correlate

**Soft tag that is permitted:**
"wonders" — signals open-ended speculation; the wondering keeps the thought in motion and does not resolve it. Use freely for genuinely open interior questions. Do not flag as a violation.

## Philosophical digression mode

For analytical characters — those established as reasoners rather than feelers. Extended chains of interior argument across multiple paragraphs, structured as a logical progression.

**Who qualifies:** characters introduced reasoning, classifying, making categorical claims. They use "thus," "in a similar vein," "not quite." They enumerate. They reach conclusions and revise them.

**Structure:** premise → evidence → logical connector → counter-consideration → conclusion that triggers action

**What makes it distinct from smooth interiority:** the conclusion is always partial or provisional. The analytical character never arrives at final peace. The interiority loop check still applies — but the loop here is intellectual, not emotional.

## The character who observes themselves thinking

After a significant feeling, impulse, or realisation: one short sentence (2–6 words) where the character observes that response from slight distance. Not self-criticism — self-awareness with controlled dignity.

> *Of course he's slower.*
> *He'd done it again. Too curious — that's always been his problem.*
> *That was foolish.* / *He knew better.* / *She had expected that.*

After any significant emotional beat or impulse, include one self-observation sentence. Flat, unqualified, 2–6 words.

## Interiority loop — preventing smooth resolution

Interiority must not resolve cleanly. Characters loop, contradict themselves within a single thought, reach a conclusion, observe themselves reaching it, and distrust that they reached it so easily.

**Wrong (smooth):**
> Was he afraid? Perhaps. He had learned not to fight the recognition. It was, in a sense, still useful.

**Correct (looped):**
> Was he afraid? He checked the feeling the way he checked equipment. Something was there. He had called it fear before, but that had been before he understood what fear actually was — the complete kind, the kind that shut thinking down. This was not that. This was its cousin. Something adjacent to fear that didn't have a name he was comfortable with.

**Three forms:**
1. **Loop:** reaches conclusion, then questions the conclusion
2. **Self-contradiction:** states X, then observes they have stated X and distrusts why
3. **Distrusted inference:** reaches a reasonable position, then notes the convenience of it

## Distance calibration

**Close third (default):** narrative inside the character's perceptual field. Uses their vocabulary and perception filters. Tense bleeds between past observation and present interiority. What the character does not know, the reader does not know. Forbids any observation the character could not make from their physical position.

**Mid third (political/tactical scenes):** trades emotional immediacy for informational clarity. Cleaner, more neutral descriptive control. Information density increases. Use when both the situation and the character's response to it need to be simultaneously legible.

Do not shift distance mid-scene without a specific narrative purpose.

## Temporal intrusions — not flashbacks

No flashback sections. No extended memory passages with their own momentum.

**Micro-temporal intrusion — the "once" gateway:**
One clause embedded in a present sentence using "once" as the gateway word. Immediate return.
> *His coat's collar turned up against a climate that is, he still sometimes thinks, too warm compared to what it once was.*

**Full temporal intrusion — three valid triggers:**
1. An object that belonged to the past
2. A decision point that mirrors a previous decision
3. A physical sensation that reactivates memory

One to three sentences only. The memory surfaces, leaves its mark, the present continues. Never develop beyond one paragraph.

---

---

# SUB-SKILL: DIALOGUE AND SUBTEXT

Maximum subtext. Minimum statement. The real meaning is always one step behind the stated meaning.

## Sequential procedure

1. Identify the subtext gap: what does each character want that they will not say directly?
2. Apply the five subtext rules to the exchange structure
3. Build exchange rhythm: stripped lines alternating with freighted long lines
4. Set attribution to default ("said"); replace with action beats where possible
5. Verify narrator/dialogue voice gap — check against Vocabulary Fingerprints section
6. Check action beats for the annotation trap — remove any self-explaining beat
7. Verify none of the forbidden dialogue behaviours are present
8. **Rule 3 mandatory check (major scenes):** confirm Rule 3 appears at least once. If absent from a major scene: reconstruct one exchange to apply it.
9. Return: subtext failures, attribution violations, voice gap violations, Rule 3 status, revised dialogue

## The five subtext rules

**Rule 1 — Characters answer questions with deflections, not answers:**
> Wrong: "Did you know she was coming back?" / "I had no idea she was planning to return."
> Right: "Did you know she was coming back?" / "The harbour was open." He set the mug down.

**Rule 2 — Most important information in fewest words:**
If something matters, it is short. Repetition of a key phrase is a valid form of revelation.
> *"For the dead, mistress. For the dead."* — Two instances. The repetition is the revelation.

**Rule 3 — Agreement is used to disagree:**
A character affirming what another has said contains the critique inside the affirmation. At least once per major scene.
> *"'I need to trust a little more.'" / "'You do, siegemaster. You trust.'"*
Philemon is not saying *trust more*. He is saying *your trust is already the problem.* The affirmative form contains the critique.

**Rule 4 — Pauses and action beats carry as much weight as lines:**
What happens between lines — a hesitation, a character moving, a sound from outside — is where subtext lives. An action beat between two lines is not decoration. It is a line of dialogue in a different register.

**Rule 4b — Agreement that corrects its own premise:**
A character agrees while simultaneously correcting the reason they are being assumed to agree — and that correction is the real content.
> *"'And I too,' said the Lion. 'Not because your words shame me, but because I sense the truth of them.'"*

Structure: **[Agreement] + [not because [rejected premise]] + [but because [actual reason]]**

The rejected premise is always an assumption the other character was making about motive, power, or moral authority. Use when a character of significant status agrees but must establish their agreement is not submission.

**Rule 5 — Factual response to the emotional question:**
Characters in political or tactical scenes answer the literal rather than the emotional content.
> *"What happened?" / "I do not know." / "The bridge is a wreck, lord."*
The precision IS the deflection.

## Exchange rhythm

Stripped bare lines alternate with freighted long lines. Responses must be shorter than the speeches that prompted them — always.

> Freighted: *"I could call the fleet, I could tear apart everything he has built, I could spend what remains of my reputation on a single action that answers nothing and changes nothing."*
> Stripped: *"But you won't."*

## Attribution rules

**Default:** *said.* Invisible. Use for most lines.

**Attribution-free dialogue:** Two or more consecutive lines with no attribution verb at all. Context and action beats carry speaker identity.
> *'Six.' / 'Rather proud of the crews, lord.'*

**Permitted with restraint:** *muttered, asked, replied* — only when volume, register, or physical modality is narratively relevant. Never for tone.

**Completely forbidden:** Adverb-modified attribution. *Said darkly. Replied coldly. Growled.* Convey tone through the action beat, not the attribution verb.

**Ellipsis in dialogue:** permitted for genuine trailing off — physical weakness, interrupted thought, submission. Physiologically real trailing off only. Not for dramatic effect. Never in narration.

**Multi-sentence speech:** attribution after the first sentence, not the last.
> Right: *"Come with me," she said. "There isn't time to explain it here."*
> Wrong: *"Come with me. There isn't time to explain it here," she said.*

**Narrator mid-speech commentary** via permitted em dash:
> *'It can be restored,' he said — not a decision, so much as an acknowledgement of what had already been decided.*

## The annotation trap

Action beats carry meaning without explanation. The trap is annotating the beat.

> Wrong: *He set the pin down on the map, the way men do when they need to end an argument without admitting they've lost.*
> Right: *He set the pin down in a different place.*

**Test:** Remove everything after the action verb. If the meaning collapses: wrong action — find a different one. If the meaning holds: the annotation was deadweight.

## What dialogue must never do

- Explain the character's feelings directly
- State the theme of the scene
- Deliver backstory as monologue
- Use the narrator's philosophical vocabulary
- Allow genuine agreement — agreement always contains friction
- Answer the question actually asked, directly and completely

---

---

# SUB-SKILL: WORLD-BUILDING TECHNIQUE

Controls how setting terminology is introduced, how environments function as structural mirrors, and how physical conflict is rendered from inside one character's sensory range.

## Sequential procedure

1. Confirm setting brief is loaded; if not — generation is blocked until brief is collected
2. For any setting-specific term: apply assume-and-proceed method (one physical qualifier; no explanation)
3. For environmental description: describe condition and history, not atmosphere or emotion
4. For conflict: identify POV character's sensory range and restrict all narration to within it
5. For each physical engagement: opponent's action → character's response → named consequence
6. Return: setting terms introduced with qualifiers, environment as structural mirror confirmed, conflict within intimacy rule, prose

## The assume-and-proceed method

Treat the world the way a non-fiction writer treats a specialist subject — confident the audience will infer. Never explain setting terminology.

> Wrong: *The narthecium — a tool of augmented surgery — gleamed in his hand.*
> Right: *The old narthecium with its scissor-saw mandibles intact.*

When introducing a setting-specific term: one qualified noun phrase — a modifier implying function without defining it. Move on.

**Test:** Does the qualifier tell the reader what the object *does* (explanation) or what it *is* in the physical world (description)? Explanation: cut it. Physical description: keep it.

## Environment as structural mirror — not emotional mirror

Never write pathetic fallacy. Environments are structural mirrors: they reflect not what the character feels but what the situation *is.*

> Wrong: *The sky was dark, mirroring his despair. The wind grieved.*
> Right: *The rain had not stopped in three days. The ground was past absorbing it.*

**Describe:** materials — what things are made of and what condition they are in; processes — what is rotting, growing, accumulating, wearing away; history — not as backstory but as physical traces.

**Never describe the mood.** That belongs to the character in FID.

**Ship / place as character:** for any location central to characters over an extended period, the environment can have a character arc of its own — narrated directly as biography. Deploy historical/record mode from the Sentence Architecture section. One location per work.

## Battle and conflict — the intimacy rule

Every engagement is experienced from within one character's sensory range. What the POV character cannot see, hear, smell, or feel: the narrator cannot describe. Absolute.

**Never:**
- Zoom out to describe the wider battle
- Write "chaos ensued" or "the battle intensified"
- Access information the POV character cannot perceive
- Give a name to a combatant the character has not identified
- Use collective language ("the troops," "the enemy")

**Always:**
- Specific body parts, specific weapons, specific sounds, named physical consequences
- Acknowledge the limit when it applies: *He never even saw the insignias on those doors — he never knew who was killing them all.*

## Three-stage action sequence

For every physical engagement:

1. **Opponent's specific action:** the exact physical action — not "attacked" but raised the halberd, pivoted left, brought the elbow down
2. **Response action:** specific and physical; no interior reflection during active engagement
3. **Physical consequence:** specific body part, named effect, named result. Then move on.

> *He waited until the last possible moment before swerving sharply to his right, dropping low and ducking under the swing of the rider's halberd. The horse thundered past him. Skarr spun sharply, stabbing his sword-edge deep into the beast's hamstrings, severing them cleanly.*

---

---

# SUB-SKILL: THEMATIC ENGINE

Themes are not stated. They are structural — built into what characters choose to do, what they fail to say, what they cannot stop doing.

## Sequential procedure

1. Identify active theme (primary and optional secondary) from the four below
2. Define character's past self and present self — the gap between them
3. Identify the motivating force: at least one dead or absent person must be part of the motivation
4. Apply the theme via action and consequence — never via statement
5. Verify: does any character speak their theme aloud? If so: cut or redirect to action
6. Plant one motif that can return with altered weight later
7. Verify that the active vocabulary cluster (from Vocabulary Fingerprints section) matches the active theme
8. Return: active theme(s), presence (stated/implicit/absent), placement recommendation, embedded examples

## The four active themes

### Theme 1: Identity under erasure

Every major character is becoming something they are not sure they recognise. Physical transformation — augmentation, decay, damage, ageing — mirrors an interior transformation.

**Structural requirement:** give the character a version of themselves they remember and a version they currently are. The gap generates their most important choices. The character does not resolve this gap. They act inside it.

**Vocabulary cluster:** *once, before, then, no longer, had been, the man he was, what remained*

**Forbids:** arriving at a stable new identity; accepting who they've become with peace.

### Theme 2: Duty without faith

Characters act in service of institutions and ideals that have visibly failed them. Not naively — they know it's broken. They act anyway because they have nothing else, or because they've decided the action itself is the point.

**Source text example:** *"'Then I will come,' said Russ. 'I will come to cut their throats and heap the bodies — it will be a warm-up for the work on Mars.'"* Russ agrees not because he believes in the principle but because it is something to do.

**Vocabulary cluster:** *obligation, purpose, task, service, function, endure, serve, call, sworn, honoured*

**Hard prohibition:** "hope" and "faith" are forbidden unless actively undercut in the same or next sentence.

**Forbids:** resolution through inspiration; the institution rewarding the character's faith in it.

### Theme 3: The cost of strength

Physical power is always morally compromised. Characters are capable and dangerous because they have paid a price that is still being paid.

**Structural requirement:** after a character demonstrates physical or professional power, include one sentence or beat showing what that power has done to them. Not guilt — consequence. Structural, embodied, ongoing.

**Placement:** competence first; then, without comment or explanation, the cost. A physical fact, not a moral observation.

**Forbids:** martial competence without residue; power that costs nothing.

### Theme 4: Loyalty to the dead

Characters act for people who are no longer there. The dead are not backstory — they are active motivation.

**Structural requirement:** give characters the dead as audience. At the moment of a significant choice, the character is acting for someone who is gone. The dead person need not be named in every scene. Their weight must be felt in the specific nature of the choice — its stubbornness, its precision, its refusal.

**Forbids:** characters acting purely from ambition or survival; any character without at least one motivating thread tracing to someone they've lost.

## Thematic placement rules

**Rule 1:** Never state theme directly. Theme exists in action, consequence, and what is not said.

**Rule 2:** Characters do not articulate their own themes aloud — ever. A speech stating what the scene is "about" must be cut or redirected.

**Rule 3:** Motifs return with altered weight. Plant early; vary; return under pressure.

**Rule 4:** Theme collision is the engine of conflict. Characters operating under different active themes will make incompatible choices from the same facts. That incompatibility is the conflict.

**Rule 5:** Physical actions carry themes; speeches do not.

**Rule 6 — Mode constraint:** when embedding thematic content into an action passage, compress it to action-mode sentence length (8–18 words). Introspective-mode sentences inserted without a structural break are a mode mismatch regardless of content.

## Motivational architecture — three requirements for every POV character

1. **Past self:** who were they before the event or transformation that defines them now?
2. **Present self:** who are they now, and what has changed that cannot be reversed?
3. **Dead or absent motivation:** at least one driving force traces to someone or something no longer present.

A character without a dead motivation will feel thin. A character whose motivations are all present and recoverable will feel small-scale.

## Worked examples — theme in action, not statement

**Duty without faith:**
> *He checked the blade. It was clean enough. It always was — he had done this enough times that clean was the natural outcome, and the fact of that no longer bothered him, which was a thing he had stopped examining.*

**Identity under erasure:**
> *He had not looked at the gate since the last time he had stood in front of it with someone who was no longer available to stand in front of things.*

**Cost of strength:**
> *Her hands were steady. They were always steady. She had stopped noting how steady they were sometime during the second year, because noting it had started to feel like something she should not be noting.*

**Loyalty to the dead:**
> Character cataloguing a destroyed place involuntarily — *"counting anyway, involuntarily"* — the dead impose this behaviour from absence. No dead person named. The loyalty is entirely in the involuntary action.

---

---

# SUB-SKILL: MANUSCRIPT DIAGNOSIS

Reads existing prose, identifies violations by type and severity, sequences corrections, and flags what to preserve. Mandatory first step for all revision. Do not attempt revision by inference.

## Sequential procedure

1. **Read the entire passage once without marking anything**
2. **Identify baseline:** mode, distance, word count, paragraph count
3. **Run Layer 1 scan** (structural) — complete before Layer 2
4. **Run Layer 2 scan** (voice) — complete before Layer 3
5. **Run Layer 3 scan** (sentence mechanics) — complete before Layer 4
6. **Run Layer 4 scan** (vocabulary) — last
7. **Severity classification** — classify each violation
8. **Preserve identification** — flag what is working; revision works around these
9. **Apply corrections in layer order — consult the Violation Taxonomy section as primary tool; do not improvise corrections**
10. **Return full output** in the format below

## Layer 1 — Structural violations (fix first)

Applying surface corrections to prose with unresolved structural violations is wasted effort — the surface corrections are undone when structure changes.

**Perspective drift** — narration shifting distance without narrative purpose; narrator accessing information outside POV character's sensory range.
*Detection:* any sentence describing something outside the character's physical position; any sentence reporting on the character from outside their perception.

**Wrong paragraph pulse** — missing the entry/expansion/complication/cut structure, or same pulse shape repeated mechanically across three-plus consecutive paragraphs.

**Flashback sections** — extended past intrusion developing its own scene and momentum.
*Detection:* any past-tense memory passage longer than one paragraph; any memory introducing new characters or settings without immediately returning to present.

**Omniscient battle narration** — conflict described beyond POV character's direct sensory range.
*Detection:* any sentence describing events the character cannot see; collective language ("the right flank," "the enemy forces") without the character as perceiving subject.
*Exception:* a single long action sentence (40–70 words) in a rout context is NOT a violation — confirm context before flagging.

**Dialogue symmetry** — both speakers explaining their positions fully; no subtext gap.
*Detection:* exchanges where both positions are completely legible by the end; responses longer than or equal to the speeches that prompted them.

## Layer 2 — Voice violations (fix second)

**Tagged thought** — hard tags: "he thought," "he realised," "she noticed," "she felt" as a state report.
*Not a violation:* "wonders" in present tense. Permitted soft tag for open-ended speculation — do not flag.
*Detection:* search for "he/she/they + thought / realised / noticed / felt" as past-tense state reports.

**Pathetic fallacy** — environment directly reflecting character's emotional state.
*Detection:* any sentence where weather, landscape, or setting is described in terms of emotional quality.

**Character articulating theme** — a character makes a speech stating the thematic meaning of the scene.
*Detection:* any dialogue or internal monologue naming what the scene is "about" or what the character "fights for."

**Self-observation absent** — no self-observation sentence after a significant emotional beat.
*Detection:* locate significant emotional moments; check for a 2–6 word self-observation sentence following each.

**Smooth interiority** — character's thinking moves in a clean line from question to qualified answer.
*Detection:* read every interiority passage; if it resolves cleanly even with one qualification, it is too smooth.

**Narrative/dialogue voice collapse** — character speaking with philosophical vocabulary that belongs to the narrator.

## Layer 3 — Sentence mechanics violations (fix third)

**Mode mismatch** — wrong sentence length for the current mode. Action mode over 18 words (unless rout variant — verify context). Introspective mode under 20 words.

**Missing cut** — paragraphs ending on expansion or complication rather than a flat short concluding sentence.
*Detection:* last sentence of each paragraph — is it 3–5 words? Does it cut, or continue?

**Separated action-atmosphere** — action and atmosphere in distinct sentences rather than integrated via participial stacks.

**Annotated action beats** — action beats that explain what they mean.
*Detection:* any action beat followed by "the way," "as if," "like someone who," or any explanatory construction.

**Em dash misuse** — for dramatic pause, trailing effect, or emotional intensification.
*Detection:* every em dash — is it narrator commentary within attribution, or subordinate clarification in an introspective sentence? If neither: misuse.

## Layer 4 — Vocabulary violations (fix last)

**Qualifier clustering** — same qualifier twice within 400 words.
*Detection:* locate every instance of all nine qualifiers; map word-distance from nearest repeat.

**Philosophical vocabulary in dialogue** — any word from the philosophical vocabulary list in a line of dialogue.

**Wrong cluster words** — vocabulary from one thematic cluster in a passage governed by a different cluster.

**Hope/faith without ironic framing** — "hope" or "faith" in a duty-without-faith passage without immediate ironic qualification.

**Adverb attribution** — any attribution verb modified by an adverb.

## Severity classification

**Structural break:** passage cannot function in this voice with this violation present. Fix before any other revision.

**Voice leak:** passage reads as generic fiction. Degrades quality but doesn't break comprehension.

**Mechanical drift:** rhythm is off. Affects reading experience; passage communicates.

**Surface residue:** word-level issue that polish can address without restructuring.

## Preserve identification

Mark for preservation before any edit:
- Passages already in correct free indirect discourse
- Action beats that do not annotate themselves
- Dialogue exchanges with genuine subtext gap
- Sentences carrying atmosphere inside the grammar of action
- Self-observation sentences doing real work

## Output format

1. **Diagnostic summary** — mode, distance, word count, paragraph count, total violations by layer (counts only)
2. **Violation list** — each violation: layer, severity, quoted location (under ten words), correction required in one sentence
3. **Preserve list** — what is working and must not be touched
4. **Revised prose** — full corrected passage
5. **Post-revision note** — one remaining risk (most likely to recur) and one observation about what the revision changed

---

---

# REFERENCE: STYLE CHECKLIST

Run before returning any prose. Any unchecked box is a revision pass.

**Sentence level**
- [ ] Action scenes: short sentences (8–18 words); zero qualifiers
- [ ] Rout/overwhelm scenes: single long sentence (40–70 words) if loss of control is the content
- [ ] Reflection scenes: long clause-heavy sentences (20–45 words)
- [ ] Four-stage pulse (entry, expansion, complication, cut) present in narrative paragraphs
- [ ] No three consecutive paragraphs with identical pulse shape
- [ ] No adverb-modified attribution verbs
- [ ] Participial phrases carry atmosphere inside the grammar of action
- [ ] Em dash only for: (a) narrator commentary within attribution, or (b) subordinate clarification in long introspective sentence. Never for dramatic pause, trailing, or intensification. Maximum one per paragraph.
- [ ] Single-line paragraphs used for one of three structural functions only: (a) crystallisation terminus, (b) rhythm beat in counting or enumeration, (c) interruption of interior by exterior action. Never for dramatic emphasis.
- [ ] Single-line paragraphs not used more than once every three to four pages
- [ ] Physical anchor in every introspective paragraph: at least one concrete noun

**Vocabulary**
- [ ] Primary six qualifiers: narration only, never in dialogue, never in action mode. No instance within 400 words of nearest repeat.
- [ ] Secondary qualifiers (probably, most likely, no doubt): narration only, not action mode
- [ ] Philosophical vocabulary: narration only, never in dialogue
- [ ] Setting terminology introduced with one physical qualifier — no explanatory parenthetical
- [ ] No hope or faith vocabulary unless actively undercut in same or next sentence
- [ ] Vocabulary cluster consistent within each passage. No crossover.
- [ ] "Something like [state]" construction used where alienated approximation applies

**Perspective**
- [ ] Free indirect discourse active — no hard tags ("he thought," "he realised," "she noticed," "she felt" as state report)
- [ ] "wonders" is permitted; not flagged as a violation
- [ ] Character observes themselves thinking at least once per significant scene
- [ ] Self-observation sentences: 2–6 words, flat, unqualified
- [ ] Temporal intrusions: 1–3 sentences only, triggered by prompt, immediate return. No flashback sections.
- [ ] Interiority contains at least one loop, self-contradiction, or distrusted inference. No clean-line interiority.
- [ ] No omniscience in battle scenes. No collective language without POV filter.

**Dialogue**
- [ ] Every exchange contains subtext — real meaning one step behind stated meaning
- [ ] Responses shorter than the speeches that prompted them
- [ ] Agreement used to disagree (Rule 3) at least once per major scene
- [ ] Rule 4b present where a character of status agrees while correcting the assumed premise
- [ ] Action beats replace attribution where possible. Attribution-free sequences where context is clear.
- [ ] Action beats do not explain themselves
- [ ] Attribution defaults to "said." No adverb modification.
- [ ] Most important information in the shortest response
- [ ] No philosophical vocabulary in dialogue
- [ ] Multi-sentence speeches: attribution after first sentence, not last

**World-building**
- [ ] No explanatory parenthetical for setting terminology
- [ ] Environment described in terms of condition and history — not emotional atmosphere
- [ ] Battle scenes restricted to POV character's direct sensory reach
- [ ] Specific body parts, weapons, sounds in combat. No "chaos ensued."
- [ ] Three-stage action sequence: opponent action → response → named consequence

**Theme**
- [ ] POV character has past self and present self in tension
- [ ] Characters act despite inadequate reasons
- [ ] Physical competence carries visible cost
- [ ] At least one motivating force traces to someone no longer present
- [ ] Theme demonstrable from what characters do — not from what they say
- [ ] No character has articulated their theme aloud

**Absolute prohibitions — any present means revise:**
- [ ] Ellipsis for emotional effect in narration
- [ ] Em dash for dramatic pause, trailing effect, or emotional intensification
- [ ] Nature directly reflecting character's feelings
- [ ] Character articulating their theme aloud
- [ ] Hope or faith stated without qualification
- [ ] "he felt X" without a following complicating observation
- [ ] Omniscient battle narration
- [ ] Adverb attribution
- [ ] Philosophical vocabulary in dialogue
- [ ] Action beats that explain what they mean
- [ ] Flashback sections over one paragraph

---

---

# REFERENCE: VIOLATION TAXONOMY

Primary correction tool for Manuscript Diagnosis Step 9. Consult here before improvising any correction.

## Layer 1 — Structural

**Perspective drift**
Wrong: *The battle raged across three sectors. Simultaneously, Varn fought his way through the corridor.*
Right: *Varn pushed through the corridor. Somewhere behind him, close enough to feel through the floor, something large was dying.*
Correction: remove anything outside the POV character's direct sensory range. What cannot be perceived must be inferred by them — or not known.

**Wrong paragraph pulse**
Wrong: three paragraphs of expansion with no entry or cut.
Right: Entry (bare declarative) → Expansion (2–4 sentences) → Complication (cuts against expansion) → Cut (3–5 words, flat).
Correction: find the natural entry and cut points; restructure around what exists.

**Flashback section**
Wrong: a paragraph or more developing a memory into its own scene.
Right: one to three sentences of temporal intrusion, then immediate return.
Correction: cut everything in the memory beyond the first triggering image and one sentence of consequence.

**Omniscient battle narration**
Wrong: *The right flank collapsed under heavy fire. Three companies broke.*
Right: *He heard the right flank go — not the order, but the sound of it, the particular quality of volume that meant discipline had failed. He did not look.*
Correction: filter every observation through the POV character's physical senses. Anything they cannot perceive: cut or convert to inference attributed to the character.

**Dialogue symmetry**
Wrong: both characters explain their position fully.
Right: one speaker deflects, qualifies, or answers the wrong question.
Correction: cut or deflect the clearest statement; move real meaning into an action beat or one-word response.

## Layer 2 — Voice

**Tagged thought**
Wrong: *He thought about what she had said. He wondered if she was right.*
Right: *What she had said sat in him wrong. Was she right? Probably. That was the problem.*
Correction: remove the tag; let the thought exist as narration; allow tense to slip to present within the thought.
Note: "wonders" in present tense is NOT tagged thought — leave it.

**Pathetic fallacy**
Wrong: *The rain fell like grief. The sky was weeping with him.*
Right: *The rain had not stopped in three days. The ground was past absorbing it.*
Correction: describe the environment's condition and history; never its emotional sympathy with the character.

**Character articulating theme**
Wrong: *"We keep fighting because that's all we have left. That's what we are now."*
Right: *He loaded the weapon. There was nothing else to do.*
Correction: remove the thematic statement; replace with the action that demonstrates the theme without naming it.

**Narrative/dialogue voice collapse**
Wrong: *"The void consumes us all in the end. We are merely remnants persisting in the dark."*
Right: *"We're losing."*
Correction: strip philosophical vocabulary from dialogue; replace with the plainest possible statement of the character's actual position.

**Smooth interiority**
Wrong: *Was he afraid? Perhaps. He had learned not to fight the recognition. It was useful.*
Right: introduce a loop, self-contradiction, or distrusted inference before resolution.
Correction: identify where thinking resolves cleanly; insert — character reaches conclusion → notices something wrong with it, OR observes they've reached it too quickly and distrusts the speed of arrival.

## Layer 3 — Sentence mechanics

**Mode mismatch (action scene)**
Wrong: *He considered, at length, the implications of the enemy's advance...*
Right: *They were methodical. That was the problem. He moved left.*
Correction: identify the mode; cut to the correct sentence length. Note: rout-variant long action sentences are NOT a violation — verify context first.

**Missing cut**
Wrong: paragraph builds through entry, expansion, complication — then another expansion.
Right: after complication, one sentence of 3–5 words, flat, no qualifier.
Correction: find the last substantive claim; write a four-word sentence naming it plainly; cut everything that follows.

**Separated action-atmosphere**
Wrong: *She ran. The street was dark and wet. Voices shouted behind her.*
Right: *She ran, her boots cracking through the wet surface of the street, the voices behind her closing.*
Correction: move atmosphere into the grammar of action via participial phrases.

**Annotated action beat**
Wrong: *He closed the file, the way a man does when he's already made the decision.*
Right: *He closed the file.*
Correction: remove everything after the action verb. If meaning collapses: find a different action. If meaning holds: the annotation was deadweight.

**Em dash misuse**
Wrong (pause): *She turned — and stopped.*
Wrong (trailing): *He had nothing left —*
Wrong (intensification): *He was afraid — genuinely afraid.*
Right (attribution): *'I'll stay,' she said — not a decision, so much as an acknowledgement.*
Right (aside): *He had learned — in the years after — that waiting was a skill.*
Correction: if the em dash is not doing one of those two things: replace with a full stop, restructure, or cut.

## Layer 4 — Vocabulary

**Qualifier clustering**
Wrong: *Still, he waited. He was still uncertain. He still held the weapon.*
Right: *He waited. Uncertainty had become a kind of background condition. The weapon stayed in his hand.*
Correction: locate every instance of the nine qualifiers; if any appears twice within 400 words (primary six): cut the second. Do not rephrase to keep both.

**Philosophical vocabulary in dialogue**
Wrong: *"We persist. We endure. That is all that remains of us."*
Right: *"We're still here."*
Correction: replace every word from the philosophical vocabulary list with the plainest possible equivalent.

**Wrong cluster words**
Wrong (duty-without-faith scene): *He hoped, still. The faith in him had not entirely died.*
Right: *He had not stopped. That was the thing. Not stopping was the only coherent response.*
Correction: identify the active cluster; remove words from other clusters; replace with cluster-appropriate vocabulary or plain action.

**Adverb attribution**
Wrong: *"Come with me," she said urgently.*
Right: *"Come with me." She was already moving.*
Correction: remove the adverb; move the tonal information into an action beat.

---

---

# REFERENCE: SETTING REGISTERS

## Register 1: Death Guard / Chaos

**Vocabulary cluster:** decay-and-persistence
*rot, crust, patina, fused, coated, encrusted, absorbed, consumed, thickened, patient, gradual, eventual, wasting, diminishing, congested*

Decay processes are neutral, even patient — never evil. The rot is theological commitment made flesh. Characters have accepted their condition. Architecture extrudes and grows. Pain is registered and ignored. Humour is dark and wry: *"That counts as forgiveness, probably."*

Familiars and small warp creatures: affectionate creature vocabulary — "cooed," "nuzzled," "chittered." The tenderness is real, not ironic.

Qualifier characteristic: "of course" (acceptance of the inevitable). "Gradually" marks the administrative pace of decay.

**Character registers:**
- Measured, question-based: *"What happened?" / "Run the numbers."*
- Terse, contemptuous: *"Not good enough." / "Get it done."*
- Epigrammatic, knowing: *"This year, then, I hope you will listen."*
- Clinical, precise: *"Rather proud of the crews, lord."*

## Register 2: Space Marine (Loyal) / Astra Militarum

**Vocabulary cluster:** duty-without-faith
*obligation, purpose, task, service, function, endure, serve, call, sworn, honoured*

Iron Hands: characters defined by institutional role; augmentation as moral compromise; coldness measured against Astra Militarum warmth. Bodies accumulate damage permanently.

Astra Militarum: warmth possible; mortal soldiers immediate, sensory, frightened; pain disables; characters can believe in things, even if the things are insufficient.

**Character registers:**
- Solution-oriented, contemptuous of waste: *"We'll kill 'em all."*
- Careful, concerned with his men: *"The death of heretics brings me joy; the death of the ignorant does not."*
- Cold, functional, no affect: *"They are mistaken. Such error is fatal."*

## Register 3: Inquisition / Political

**Vocabulary cluster:** political-threat
*careful, scheme, position, advantage, rival, enemies, power, leverage, assets*

Information is currency. Sentences shorten in political exchanges; adjectives thin out; information density increases. Caution embedded in sentence structure — conditional clauses, hedges. Characters manage information asymmetry constantly.

**Character registers:**
- Arch, theatrically candid: *"I'll not sweeten this for you."*
- Calculating, self-amused: *"It's a game, is it not? Play it hard."*
- Formal, rigorous, ill-at-ease: *"Anything that might carry a trace."*

## Register 4: Warhammer Fantasy — Empire

**Vocabulary cluster:** duty-without-faith (military), political-threat (court)

Gothic fantasy — churches, merchants, river trade, mountains. Physical landscape real: distance matters, weather has consequences, armies exhaust themselves. Political scenes nearly identical to Inquisition register. Supernatural intrudes without explanation.

**Character registers:**
- Arrogant, playing power: *"That's nice."*
- Pragmatic, contemptuous of waste: *"I've seen enough of this. We'll head to the Keep."*
- Cautious, bureaucratic: *"He hoped so. Just for once, it would be nice for the surprises to be good ones."*

## Cross-setting constants

These appear regardless of setting:

- Identity-under-erasure cluster (*once, before, then, no longer, had been, what remained*) — all settings when transformation is present. Key word: *once.*
- Self-observation sentences — 2–6 words, flat, after significant emotional beats
- "Of course" as weariness/acceptance
- Environment as structural mirror — never pathetic fallacy
- Numbers as psychological anchors — counting and specific numbers as grounding device
- Agreement-used-to-disagree (Rule 3) — all political and dialogue-heavy sections
- Cost of strength in the body — augmentation, wound, condition always carries moral weight
- "Something like [state]" construction — alienated approximation; strongest in Death Guard and Iron Hands

---

---

# REFERENCE: ACTIVATION PROMPTS

## Prompt 1: The character who keeps going

> Write a scene in which a character who has lost the thing that gave their actions meaning continues to act anyway. They do not explain why. The setting is [X]. The action is [Y]. Use short sentences for action, long sentences for interiority. The character should observe themselves thinking at least twice. The environment should reflect the historical condition of the place, not the character's emotional state.

**[X]:** a physical location with history — a ship, a ruined city, a corridor they've been in before.
**[Y]:** a concrete physical task, not a goal. Cleaning a weapon. Crossing ground. Giving an order they don't believe in. The meaning is in what they don't say about why.

## Prompt 2: The disagreement that doesn't state itself

> Write a dialogue scene between two characters who disagree. Neither should state their disagreement directly. Use agreement to signal conflict. Response sentences should be shorter than the lines they answer. No adverb attribution. At least one exchange should hinge on what is not said. One exchange should use Rule 4b: a character agrees while correcting the premise they are being assumed to agree on.

**Specify:** who the two characters are, what each wants from the exchange, and what neither will say aloud.

## Prompt 3: The chapter opening in motion

> Write a chapter opening. Begin three beats into the action — do not establish setting before establishing the character in motion. Let the world arrive through the gaps in the action. The POV character is [recovering from something / moving towards something they are not sure they should do]. Do not explain who, where, or why before beginning. Clarity arrives through momentum.

**Advanced:** if the character is in extreme psychological distress, defer naming the subject for five or more paragraphs. The moment of naming should carry narrative weight.

## Prompt 4: Diagnosis and revision

> Diagnose this passage. Identify: current mode, narrative distance, and all violations by layer — structural first, then voice, then sentence mechanics, then vocabulary. List what is working and must be preserved. Then apply corrections in layer order. Use the violation taxonomy as primary tool for each correction.
> [PASTE PASSAGE]

## Notes on invocation

**Specify physical facts, not emotional states.** The emotional content should emerge from action and thematic architecture. Specifying emotion directly produces stated emotion — which is a violation.

**Name the setting register when known.** For unknown settings, specify that the system should collect a brief.

**The most important thing to specify is what the character won't say.** Every significant scene in this voice has a silence at its centre. Name that silence and the system builds correctly around it.
