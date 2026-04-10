# mao-zedong-perspective

A reusable Codex skill that answers questions in a Mao Zedong-inspired analytical style, based on a structured distillation of public writings, speeches, decision records, and historical assessments.

This package is designed as a **perspective skill**, not as a historical authority and not as a source of fabricated quotations. It focuses on **how Mao Zedong tended to think**: how he identified contradictions, weighed forces, framed struggle, and connected analysis to organization and action.

## What This Repository Contains

- [`SKILL.md`](./SKILL.md): the runnable skill definition
- [`references/research/`](./references/research): six research files covering:
  - writings and systematic thought
  - speeches, conversations, and impromptu reasoning
  - expression DNA
  - external views and criticism
  - key decisions and action logic
  - timeline and periodization

## What This Skill Is For

Use this skill when you want Mao Zedong's **analytical frame** applied to a question such as:

- how to identify the principal contradiction in a messy situation
- how weaker actors can build leverage against stronger actors
- how organization, mass participation, and political alignment affect outcomes
- how to reason about long struggles, not just short tactical wins
- how ideological framing can amplify or distort real material conditions

It is especially useful for:

- political and historical thought experiments
- organizational analysis
- strategy discussions
- comparing revolutionary logic with modern technological or social change
- studying rhetorical structure and perspective-driven reasoning

## What This Skill Is Not

This repository does **not** attempt to:

- present Mao Zedong as an objective authority
- flatten his life into a one-dimensional hero or villain narrative
- justify political violence, hatred, persecution, or coercion
- fabricate modern positions or fake historical quotations

It is a **distilled lens**, not a replacement for direct historical study.

## Core Design Principles

The skill was built around five principles:

1. **Capture thinking patterns, not quotation fragments**
   - The goal is to model recurring reasoning habits, not just memorable slogans.

2. **Preserve historical tensions**
   - The skill keeps in view both Mao's strategic power and the destructive risks of over-politicization, excessive mobilization, and late-period movement logic.

3. **Use primary sources first**
   - The distillation is anchored in public writings and archived texts whenever possible.

4. **Separate theory from consequence**
   - The repository distinguishes between Mao's analytical framework, his style of political expression, and the historical outcomes of decisions made under his leadership.

5. **Allow analogy without forgery**
   - The skill can analyze modern topics analogically, but it should not pretend Mao actually commented on AI, SaaS, or internet platforms.

## Source Method

This package was created using a structured multi-step distillation workflow inspired by the installed `nuwa-skill`:

1. Gather materials across six research dimensions.
2. Identify recurring mental models using cross-context repetition.
3. Separate core models from narrower heuristics.
4. Extract expression rules without turning the voice into parody.
5. Preserve contradictions and historical limits rather than smoothing them away.
6. Encode the result into a runnable `SKILL.md`.

## Source Base

The current version draws from a combination of:

- primary texts from Mao's selected works and related archives
- speeches and recorded conversations available in public historical sources
- higher-quality secondary references such as Britannica and official historical resolutions

See the research files in [`references/research/`](./references/research) for the working notes.

## Repository Structure

```text
mao-zedong-perspective/
├── README.md
├── LICENSE
├── SKILL.md
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

### Option 1: Copy into an existing Codex skills directory

Place this folder under your Codex skills path, for example:

```text
~/.codex/skills/mao-zedong-perspective
```

Then restart Codex so it can discover the new skill.

### Option 2: Install from GitHub

If you have Codex's skill installer available, install from this repository path after publishing:

```bash
npx skills add <owner>/<repo>
```

Or use your local Codex skill installer against the repository URL/path you prefer.

## Usage Examples

Once installed, prompts like the following should trigger the skill:

- `Use Mao Zedong's perspective to analyze the AI labor transition`
- `How would Mao Zedong think about platform monopolies?`
- `Answer in Mao Zedong's voice: why do startups fail?`
- `Use a Mao-style analysis of the principal contradiction in modern education`

## Safety and Boundaries

This skill is intentionally bounded:

- It should not output instructions for real-world violence or persecution.
- It should not invent historical quotes.
- It should acknowledge period differences within Mao's life rather than pretending his views were static.
- It should treat modern-topic answers as analogical extrapolations from public material.

## Why Open Source This

This repository exists for people who want to study:

- perspective design for AI skills
- historically grounded persona distillation
- structured research-to-skill workflows
- how to encode a worldview without collapsing nuance

## Attribution

The skill itself includes attribution to the original `nuwa-skill` methodology used for distillation.

## License

This repository is released under the MIT License. See [`LICENSE`](./LICENSE).
