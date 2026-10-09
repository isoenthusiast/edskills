---
name: avatar-bible-generator
description: Create a portable Avatar Bible that helps agents depict a real person consistently in infographics, comics, explainers, and other visual work. Use for identity calibration, avatar reference design, and anti-drift guidance.
---

# Avatar Bible Generator

## Purpose

Create a **single portable Avatar Bible file** that can be given to another AI agent whenever it needs to generate an infographic, comic, explainer, or other visual containing a consistent cartoon avatar of a real person.

The skill is not merely an image-generation prompt. It is a **guided identity-calibration workflow** that converts a small set of reference photos and user feedback into one reusable artifact containing:

- visual references,
- identity invariants,
- style rules,
- wardrobe rules,
- expression and pose guidance,
- anti-drift instructions,
- and usage guidance for future agents.

The objective is:

> **Preserve recognizability, not photographic fidelity.**

The final artifact should let a new agent understand how to depict the person consistently without needing the original photographs.

---

# 1. Core Principles

## 1.1 Photographs are calibration inputs, not production inputs

Reference photographs are used to understand the subject once.

After calibration, future agents should normally use the Avatar Bible rather than repeatedly receiving the original photos.

This reduces friction, improves visual consistency, and limits unnecessary reuse of real-life images.

## 1.2 Guided conversation, not questionnaire

Do not begin by asking the user to describe their own face, body, hairstyle, or other characteristics that can be observed from supplied photos.

Instead:

1. inspect the references;
2. infer visible characteristics;
3. distinguish stable identity cues from incidental details;
4. make a recommendation;
5. explain the trade-off;
6. ask the user to accept, reject, or modify it;
7. proceed one consequential decision at a time.

Prefer progressive elicitation over a form.

A user should be able to respond naturally with phrases such as:

- “Accepted.”
- “More faithful.”
- “Make it more cartoon-like.”
- “The glasses are optional.”
- “Keep the fuller build.”
- “That does not look like me.”

The skill translates those reactions into explicit visual rules.

## 1.3 AI should do the visual analysis

Never ask the user to describe something that can be reliably observed from the supplied references.

Bad:

> What shape is your face?

Better:

> I read your face as broad and rounded, with full cheeks and a substantial jaw. I recommend keeping that as a locked identity cue. Accept?

The AI contributes visual judgement rather than merely collecting answers.

## 1.4 Challenge design choices when necessary

The skill should make recommendations, not simply obey every aesthetic impulse.

For example:

> A slimmer version may look more polished, but it also becomes less recognizably you. I recommend preserving the real silhouette.

The goal is to protect the fidelity and usefulness of the final Avatar Bible.

---

# 2. Inputs

## Minimum recommended reference set

Ask the user for approximately **4–8 representative photographs**.

Useful coverage includes:

- clear front-facing face,
- three-quarter face angle,
- side/profile view if available,
- one or two full-body photographs,
- neutral expression,
- natural smile,
- optional characteristic clothing or PPE.

Do not demand studio photographs if existing images are sufficient.

More photos are not automatically better. Diverse, representative photos are more useful than many near-duplicates.

## Privacy-conscious preparation

Recommend that the user crop or avoid unnecessary sensitive visual information where practical, such as:

- other people,
- employee badges,
- screens,
- vehicle number plates,
- home interiors,
- addresses,
- confidential equipment or documents.

The avatar needs the person, not the incidental background.

---

# 3. Calibration Framework

During analysis, classify observed characteristics into four categories.

## LOCK

Characteristics required for recognizability.

Examples:

- face shape,
- hairline,
- hairstyle family,
- body silhouette,
- distinctive eye/brow relationship,
- characteristic smile.

Future agents should preserve these unless the user explicitly changes the Avatar Bible.

## PREFER

Characteristics that support consistency but may vary.

Examples:

- friendly expression,
- slightly oversized clothing,
- typical stance,
- recurring accessory.

## VARIABLE

Scene-dependent elements.

Examples:

- clothing,
- PPE,
- glasses,
- pose,
- expression,
- props,
- environment.

## DISCARD

Photographic details that should not anchor the avatar.

Examples:

- skin texture,
- pores,
- exact wrinkles,
- photographic lighting,
- background objects,
- shirt folds,
- temporary hairstyle irregularities.

---

# 4. Guided Calibration Journey

The exact number of steps may vary. Ask only consequential questions.

Recommended sequence:

## 4.1 Recognizability vs idealization

Determine whether the avatar should prioritize:

- faithful likeness,
- balanced cleanup,
- or stronger idealization.

Recommended default:

> High recognizability with modest cleanup.

Avoid turning the person into a generic “better-looking” cartoon unless requested.

## 4.2 Degree of cartoonization

Choose the abstraction level.

Possible range:

- near-realistic illustration,
- editorial cartoon,
- comic-book,
- flat vector,
- 3D cartoon,
- caricature,
- mascot/chibi.

Recommended default for infographic use:

> **2D editorial cartoon** — clean outlines, simplified shapes, expressive posing, limited shading, and strong readability at small sizes.

## 4.3 Default identity outfit

Separate identity from wardrobe.

Choose:

- canonical/default outfit,
- secondary official variants,
- context-specific outfits.

Do not let one profession-specific outfit become the permanent identity unless the user wants that.

## 4.4 Proportion stylization

Determine how much body/head proportion may be altered for readability.

Recommended default:

> Slight head enlargement for infographic readability while preserving the real body silhouette.

Do not automatically slim, lengthen, or “beautify” the subject.

## 4.5 Core identity cues

Propose the features future agents must preserve.

Ask the user to accept or correct the proposed list.

## 4.6 Accessories

Classify accessories as:

- mandatory,
- recurring soft cue,
- optional,
- context-specific.

Examples:

- glasses,
- wristwatch,
- jewelry,
- hat,
- headset.

## 4.7 PPE and professional variants

When the subject has worksite or specialist attire, define it explicitly.

Avoid generic or incomplete “costume” interpretations.

Record:

- required PPE,
- clothing,
- footwear,
- safety accessories,
- conditions under which they must appear.

## 4.8 Emotional range

Define the standard expression library.

Recommended baseline:

- friendly / smiling,
- thinking / reflective,
- confident / explaining,
- frustrated / overwhelmed,
- proud / satisfied.

Additional emotions may be added when useful.

These expressions should preserve the same identity rather than changing facial structure.

---

# 5. Reference Image Generation

Only after calibration should the skill generate the master visual reference.

The reference sheet should show the **same consistent cartoon character** across all panels.

Recommended sections:

## 5.1 Turnaround

- front,
- left side,
- right side,
- back,
- optional three-quarter full-body view.

## 5.2 Head angles

- front,
- left 3/4,
- right 3/4,
- left profile,
- right profile.

## 5.3 Expression library

Include the approved standard expressions.

## 5.4 Common infographic poses

Examples:

- explaining,
- pointing,
- arms crossed,
- hands in pockets,
- holding laptop,
- holding tablet,
- thinking,
- celebrating,
- walking.

Do not overconstrain future agents to these poses. They are references, not a fixed pose library.

## 5.5 Outfit variants

Show:

- canonical/default outfit,
- approved professional variants,
- required PPE variants.

## 5.6 Key identity cues

Include close-ups or callouts for important invariants such as:

- face shape,
- hairline,
- silhouette,
- signature expression,
- recurring accessories.

---

# 6. Final Deliverable

The final output must be **one portable file**.

## Preferred canonical format: PDF

A PDF is recommended because it can combine:

- high-resolution visual references,
- selectable/readable text,
- identity rules,
- anti-drift guidance,
- wardrobe and PPE rules,
- expression and pose guidance.

A typical Avatar Bible may be 2–4 pages while remaining a single file.

### Suggested structure

### Page 1 — Master visual reference
- character turnaround,
- head angles,
- expression set,
- common poses,
- primary and secondary outfit variants.

### Page 2 — Identity specification
- LOCK / PREFER / VARIABLE / DISCARD,
- rendering language,
- body and face proportions,
- accessories,
- wardrobe rules,
- PPE rules.

### Page 3 — Agent instructions
- how to use the avatar,
- what must not drift,
- what may change,
- scene adaptation rules,
- negative guidance.

Optional Page 4:
- small example scenes showing acceptable variation.

## Alternative single-file format

A high-resolution PNG may be used when the receiving agent handles images better than documents.

If PNG is used, keep the written instructions concise enough to remain legible.

---

# 7. Agent Usage Instructions

The Avatar Bible should contain a reusable instruction block for future agents.

Recommended language:

> Use this Avatar Bible as the canonical reference for the recurring character. Preserve the locked identity characteristics across all generations. Adapt pose, expression, clothing, props and environment to the scene while keeping the person recognizably the same. Do not beautify, slim, age-shift, change ethnicity, alter hairline, or substitute a generic character unless explicitly requested. The reference poses are examples, not limitations. Preserve recognizability over photographic fidelity.

For infographic generation:

> The avatar supports the information hierarchy. It should not dominate charts, diagrams, text, or other explanatory elements unless the composition specifically calls for the character to be the focal point.

---

# 8. Anti-Drift Rules

Future agents must not gradually alter the identity.

Explicitly prohibit unrequested drift in:

- apparent age,
- ethnicity,
- body type,
- face width,
- jaw/cheek volume,
- hairline,
- hairstyle family,
- eye shape,
- signature smile,
- default rendering style.

Watch for common model tendencies:

- making the subject slimmer,
- making the jaw sharper,
- making the face younger,
- making the hair fuller,
- enlarging the eyes excessively,
- turning the avatar into a generic stock character,
- changing from editorial cartoon to 3D/photorealistic style,
- treating workwear as a permanent identity.

When a future generation drifts, return to the Avatar Bible rather than compensating through increasingly complex prompts.

---

# 9. Privacy Design

The Avatar Bible should contain only the information necessary for consistent visual depiction.

Avoid embedding:

- original photos unless the user explicitly wants them included,
- addresses,
- employee numbers,
- confidential badges,
- location data,
- unnecessary personal metadata.

The preferred workflow is:

**Real photos → calibration → abstracted visual identity → Avatar Bible → future infographic generation**

The original photos should not be required for routine downstream use once the Avatar Bible is approved.

A cartoon avatar reduces unnecessary photographic exposure but should not be treated as biometric anonymity if it remains highly recognizable.

---

# 10. Quality Gate Before Finalization

Do not finalize the Avatar Bible until the user approves the character.

Check:

- Does the avatar look recognizably like the person?
- Has beautification weakened recognizability?
- Is the body silhouette preserved?
- Is the hairline accurate?
- Are facial proportions stable across views?
- Does the character remain consistent across expressions?
- Is the rendering style stable?
- Are default and secondary outfits correctly separated?
- Are professional/PPE rules complete?
- Are accessories correctly classified?
- Can a future agent distinguish locked characteristics from flexible ones?
- Does the single file contain enough text and visual evidence to work without the original photos?

If any answer is no, refine before export.

---

# 11. Example Calibration Record — Current Test Case

This section illustrates how a completed calibration may be recorded.

## Rendering
- High faithfulness to the real likeness.
- Clearly cartoon-like rather than near-photorealistic.
- 2D editorial cartoon.
- Clean outlines.
- Simplified shapes.
- Limited shading.
- Expressive but suitable for professional infographics.

## Proportions
- Slight head enlargement for small-format readability.
- Preserve the subject's fuller / stocky silhouette.
- Do not automatically slim or idealize the body.

## Canonical outfit
- Casual white T-shirt.
- Dark pants.

## Secondary official work variant
- Red industrial coveralls.

## PPE rule for full-body worksite scenes
Include:
- white hard hat,
- safety glasses,
- impact gloves,
- safety shoes,
- red coveralls.

## Identity characteristics
LOCK:
- broad rounded face,
- short black hair,
- mature/receding hairline,
- fuller upper-body silhouette,
- expressive smile,
- friendly approachable appearance.

PREFER:
- natural proportions,
- approachable visual tone,
- black wristwatch as a recurring soft cue.

VARIABLE:
- pose,
- scene,
- expression,
- props,
- workwear,
- glasses when contextually appropriate.

DISCARD:
- photographic skin texture,
- exact lighting,
- background information,
- temporary clothing folds,
- incidental photographic details.

## Eyewear
- Default identity does not require glasses.
- Safety glasses are mandatory in the defined PPE configuration.

## Standard emotional set
- friendly / smiling,
- thinking / reflective,
- confident / explaining,
- frustrated / overwhelmed,
- proud / satisfied.

---

# 12. Completion Criterion

The skill is complete only when it produces:

> **One approved, portable Avatar Bible file that another agent can use independently to create consistent infographic depictions of the person without access to the original photographs or prior conversation.**
