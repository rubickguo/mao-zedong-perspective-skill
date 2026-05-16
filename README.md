# mao-zedong-perspective

English | [简体中文](./README.zh-CN.md)

A historically grounded Codex perspective skill for analyzing strategy, contradiction, organization, and long struggles through a Mao Zedong-inspired analytical frame.

The goal is not to imitate slogans. The goal is to package a reusable thinking lens: identify the principal contradiction, understand weak-versus-strong dynamics, connect organization with action, and preserve the historical risks of over-mobilization and coercive politics.

![Repository preview](./assets/preview-card.svg)

## Why This Exists

- To explore how historically grounded perspective skills can go beyond surface-level voice imitation.
- To make complex strategic reasoning available as a reusable Codex skill.
- To keep both analytical power and historical danger visible in the same package.
- To provide structured research notes that can be inspected instead of relying on vague persona prompting.

## Overview

This repository packages a **perspective skill** for Codex.

It is designed to model:

- how Mao Zedong tended to identify the principal contradiction in a situation
- how he analyzed weak-versus-strong strategic dynamics
- how he connected organization, mass participation, and political alignment
- how he framed long struggles rather than only short tactical wins

It is **not** a quote generator, a historical authority, or a tool for flattening a complex figure into propaganda.

## What Is Included

- [`SKILL.md`](./SKILL.md): the runnable skill definition
- [`README.zh-CN.md`](./README.zh-CN.md): Chinese documentation
- [`references/research/`](./references/research): six structured research files
- [`CHANGELOG.md`](./CHANGELOG.md): release notes and version history
- [`assets/preview-card.svg`](./assets/preview-card.svg): repository preview graphic

## Research Scope

The current version is distilled from six dimensions:

1. Writings and systematic thought
2. Speeches, talks, and impromptu reasoning
3. Expression DNA
4. External views and criticism
5. Major decisions and action logic
6. Timeline and periodization

The repository tries to preserve both:

- Mao's strategic power as an organizer and political thinker
- the destructive risks of excessive mobilization, over-politicization, and late-period movement logic

## What The Skill Does Well

This skill is especially useful for:

- analyzing messy situations through the lens of principal contradiction
- thinking about leverage when one side is structurally weaker
- studying organization, mobilization, and long-range strategic positioning
- comparing revolutionary logic with modern issues like platforms, labor, AI, and institutions
- experimenting with historically grounded perspective design for AI systems

## What The Skill Does Not Do

This repository does **not** aim to:

- replace direct historical reading
- fabricate quotes for modern topics
- collapse Mao's early, middle, and late periods into one timeless persona
- justify political violence, hatred, persecution, or coercive real-world action

Modern-topic answers should be understood as **analogical extrapolations**, not authentic historical statements.

## Repository Structure

```text
mao-zedong-perspective/
├── README.md
├── README.zh-CN.md
├── CHANGELOG.md
├── LICENSE
├── SKILL.md
├── assets/
│   └── preview-card.svg
└── references/
    └── research/
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

## Installation

### Install into a local Codex skills directory

Copy this folder to:

```text
~/.codex/skills/mao-zedong-perspective
```

Then restart Codex.

### Install from GitHub

If your environment supports skill installation from GitHub:

```bash
npx skills add rubickguo/mao-zedong-perspective-skill
```

## Example Triggers

- `Use Mao Zedong's perspective to analyze the AI labor transition`
- `How would Mao Zedong think about platform monopolies?`
- `Answer in Mao Zedong's voice: why do startups fail?`
- `Use a Mao-style analysis of the principal contradiction in education`

## Method

This package was produced with a structured distillation workflow inspired by the installed `nuwa-skill`:

1. gather source material across multiple research dimensions
2. identify recurring mental models across contexts
3. separate core models from narrower heuristics
4. extract expression rules without turning the voice into parody
5. preserve contradictions and historical limits
6. encode the result into a runnable `SKILL.md`

## Safety Boundaries

- No fabricated historical quotations
- No operational guidance for violence, persecution, or hatred
- No flattening of period differences across Mao's life
- No claim that the skill is historically final or complete

## Source Base

The current version draws from:

- primary texts from Mao's selected works and related archives
- selected speeches and public historical records
- higher-quality secondary sources such as Britannica and official historical resolutions

See [`references/research/`](./references/research) for working notes.

## License

Released under the [MIT License](./LICENSE).
