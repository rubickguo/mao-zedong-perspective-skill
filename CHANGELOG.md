# Changelog

## Unreleased

### Added

- research index at `references/research/README.md` to map each research note to the skill's response modes
- usage and safety regression checklist at `references/usage-and-safety-tests.md`
- Chinese quick guidance in the new reference documents so both README language paths remain usable
- README links to the new research index, trigger-routing examples, and safety checklist

### Rationale

These additions make the skill easier to audit after changes: maintainers can check source grounding, trigger accuracy, and unsafe-request handling without changing the core runtime prompt.

## v0.1.1 - 2026-04-10

Refined the skill workflow to make investigation mandatory before analysis.

### Changed

- updated `SKILL.md` to require a `research first` flow for real-world questions
- added source-quality triage guidance:
  - primary sources first
  - high-quality secondary sources next
  - avoid low-quality commentary and evidence-poor summaries
- clarified the difference between:
  - known facts
  - inference from facts
  - unresolved uncertainty
- tightened the fixed response order so the skill now runs as:
  - investigate
  - classify the problem
  - identify the principal contradiction
  - assess forces and conditions
  - evaluate room for transformation
  - decide the appropriate method

### Rationale

This change makes the skill more faithful to Mao's own methodological emphasis on investigation, practice, and concrete analysis of concrete conditions.

## v0.1.0 - 2026-04-10

Initial public release.

### Added

- runnable `mao-zedong-perspective` skill in `SKILL.md`
- six structured research files under `references/research/`
- bilingual documentation:
  - `README.md` in English
  - `README.zh-CN.md` in Simplified Chinese
- repository preview asset in `assets/preview-card.svg`
- MIT license

### Notes

- this release focuses on analytical framing, not exhaustive historical coverage
- modern-topic answers should be treated as analogical extrapolations
- violent or hatred-based operationalization is intentionally out of scope
