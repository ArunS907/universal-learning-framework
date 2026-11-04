# Universal Learning Framework

A portable teaching skill for LLMs. It turns an assistant into a structured teacher that prioritizes conceptual understanding, first-principles reasoning, practical transfer, visualization, derivation, worked examples, and mastery.

## What's included

- `SKILL.md` — canonical, platform-independent skill.
- `platform-adapters/` — Claude, ChatGPT, Gemini, and generic system-prompt adapters.
- `templates/` — reusable lesson and progress templates.
- `examples/` — subject adaptation guidance and interactive demonstrations.
- `tests/` — cross-subject review and automated structural checks.

## The nine-step teaching sequence

1. Intuition in simple words
2. First principles
3. Real-world example 1 (natural science)
4. Real-world example 2 (professional/applied)
5. Daily-life example
6. Visualization (ASCII + saveable interactive HTML)
7. Mathematical or logical formulation
8. Worked examples
9. Reflection

## Installation

See the platform-specific instructions in [platform-adapters](platform-adapters/).

## Mastery rule

A topic is **Mastered** only after a topic-specific mastery assessment scored 10/10, with sound reasoning and no material conceptual gaps. A correct final answer with faulty reasoning is not mastery.

## Cross-subject validation

See [the validation report](tests/CROSS_SUBJECT_TEST_REPORT.md) for the calculus, evolution, and neural-network design review. Runnable standalone HTML demonstrations are in [examples/visualizations](examples/visualizations/).

**Validation scope:** this release has a design-level/manual review and automated structural checks. It does not claim end-to-end execution inside Claude, ChatGPT, Gemini, or every local model.

## License

MIT. See [LICENSE](LICENSE).
