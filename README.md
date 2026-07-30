# looksmaxxing skill

A practical AI skill for hair, grooming, glasses, skincare, clothing and facial presentation.

Not a beauty-score machine. Not a diagnosis engine. Not a promise that every face should converge on the same guy with a five-millimetre beard fade.

It helps turn a vague question — *what should I do with my hair? why do these frames feel wrong? how do I look less washed out on camera?* — into a small set of reversible, explainable things to try.

## what it does

- reads visual/style questions through hairline, hair quality, facial balance, grooming, glasses, colour and context;
- gives a priority stack rather than twenty “optimisations”;
- distinguishes practical styling advice from individual preference and medical territory;
- provides a structured knowledge base for AI assistants and human readers.

## what it does not do

- assign attractiveness scores or rank people;
- diagnose skin, hair loss, health or mental-health conditions;
- infer personality, ethnicity, health or genetics from appearance;
- prescribe medication, diets, supplements, injectables or surgery;
- turn a single selfie into fake biometric certainty.

## install

### as a skill

Copy this folder into the skill directory of an assistant that supports `SKILL.md`, then point the assistant at it.

```bash
git clone https://github.com/raysvitla/looksmaxxing-skill.git
# copy or symlink the repo into your assistant's skill directory
```

The main instructions live in [`SKILL.md`](./SKILL.md). Topic notes are under [`knowledge/`](./knowledge/).

### as a reference

Start here:

| question | file |
| --- | --- |
| haircut, hairline, density, texture | [`knowledge/hairstyles-guide.md`](./knowledge/hairstyles-guide.md) |
| glasses and frames | [`knowledge/glasses-selection-guide.md`](./knowledge/glasses-selection-guide.md) |
| grooming and male facial hair | [`knowledge/mens-specific.md`](./knowledge/mens-specific.md) |
| skincare, dark circles, puffiness | [`knowledge/skincare-guide.md`](./knowledge/skincare-guide.md) |
| clothing and colour | [`knowledge/style-principles.md`](./knowledge/style-principles.md) |
| myths / things not worth chasing | [`knowledge/common-mistakes.md`](./knowledge/common-mistakes.md) |

## the method

The usable hierarchy is deliberately boring:

1. **start with the desired read** — sharper, softer, more formal, more like yourself, better on camera, lower maintenance;
2. **change reversible things first** — cut, part, styling, skin basics, glasses, facial hair, clothing, light;
3. **make a few moves, not a total life redesign**;
4. **keep observation separate from judgement**;
5. **refer medical questions to medical professionals.**

The original source corpus includes public QOVES Studio YouTube material plus linked research context. This repository contains Ray Svitla’s structure, prompts and synthesis — it is not affiliated with QOVES and does not reproduce or license their work. See [`SOURCES.md`](./SOURCES.md).

## example prompt

> I have thick, slightly wavy hair, wear glasses, and want a cut that reads intentional but needs little styling. I like short sides but hate looking like a finance bro. What should I ask my barber for?

A good answer should name the relevant constraints, give 2–3 options with trade-offs, say what to avoid **for that goal**, and include a short barber script.

## contribution

Useful contributions are welcome:

- source corrections and stronger citations;
- clearer, less absolutist wording;
- image/camera caveats;
- practical experience that can be separated from claims of fact.

Please do not submit copied transcripts, scraped private images, individual “ratings,” medical claims without credible sourcing, or advice designed to shame people into buying things.

## license and source boundary

The **original repository structure and instructions** are MIT-licensed. Third-party source material remains with its respective owners. No affiliation with or endorsement by QOVES Studio is claimed.

See [`LICENSE`](./LICENSE), [`NOTICE.md`](./NOTICE.md), and [`SOURCES.md`](./SOURCES.md).

---

Built by [Ray Svitla](https://github.com/raysvitla) as part of an ongoing **one-person state** garden: small tools for seeing and acting a little more clearly.
