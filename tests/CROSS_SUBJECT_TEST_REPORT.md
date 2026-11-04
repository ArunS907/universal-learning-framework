# ULF v1.0.0 — Cross-subject validation

## Scope

The skill was reviewed against three deliberately different subjects to test whether the same nine-step teaching sequence can adapt without forcing unsuitable examples or formalism.

## Test matrix

| ID | Subject | Core adaptation requirement | Expected visualization | Main failure to watch |
|---|---|---|---|---|
| ULF-01 | Calculus: derivatives | Derive rate of change from average rate over a shrinking interval | Tangent line and adjustable x-position | Formula before intuition; derivative rule asserted without derivation |
| ULF-02 | Biology: evolution by natural selection | Explain variation, heritability and differential reproductive success | Trait-frequency change across generations | Teleological language; implying individuals evolve because they need to |
| ULF-03 | Technology: neural networks | Explain weighted inputs, activation, loss and learning through parameter updates | Adjustable single-neuron model | Anthropomorphism; treating a single-neuron demo as a full modern neural network |

## Review criteria

1. All nine steps are present and in the prescribed order.
2. Intuition precedes formal notation.
3. First principles explain the problem and mechanism.
4. Natural-science example is relevant and accurate.
5. Professional/applied example is concrete and appropriate.
6. Daily-life example maps to the concept without overclaiming.
7. Visualization is usable and accurately labelled.
8. Mathematical/logical formulation is derived and symbols are defined.
9. Worked examples show reasoning and interpretation.
10. Reflection explains why the concept matters.
11. Quiz includes conceptual, applied, mixed-difficulty, reflection and repair/foundation-check questions.
12. Progress language does not claim mastery without a topic-specific 10/10 assessment and sound reasoning.

## ULF-01 — Calculus: derivatives

**Expected teaching path:** instantaneous rate of change → average rate of change → shrinking interval → limit definition → derivative rules and worked calculations.

**Subject-fit checks:** A natural-science example can use velocity as the rate of change of position. An applied example can use marginal cost or changing demand. A daily-life example can use a car's speedometer, noting that a real speedometer estimates speed over a short interval.

**Result:** PASS for subject adaptation and visualization design. The skill requires derivation from average rate of change rather than presenting derivative rules as unexplained facts.

## ULF-02 — Biology: evolution by natural selection

**Expected teaching path:** population-level change in inherited trait frequencies → variation, inheritance and differential reproductive success → change across generations.

**Subject-fit checks:** Antibiotic resistance is appropriate when explained as selection among heritable variants, not an individual bacterium deliberately adapting. Applied examples can discuss pest management or conservation.

**Result:** PASS for scientific framing and subject adaptation. The skill warns against teleological explanations and requires caveats for simplified models.

## ULF-03 — Technology: neural networks

**Expected teaching path:** a model adjusts internal parameters to reduce prediction error → weighted sum and activation → loss and parameter updates.

**Subject-fit checks:** A science example can use a simplified sensory classification task. Applied examples can use spam classification or quality inspection. A daily-life example can explain recommendation ranking while clarifying that real systems are more complex.

**Result:** PASS for technology adaptation and visualization design. The skill requires algorithm explanations, edge cases, trade-offs, and a warning against treating a single-neuron demo as a complete modern network.

## Overall result

**PASS — framework structure and cross-subject adaptation review.**

This is a design-level/manual validation of the skill specification and sample visualization concepts. It is not a claim that Claude, ChatGPT, Gemini, or every local model has been run automatically.

## Next validation

Run the same three test prompts against each target model and compare generated lessons with this checklist. Record platform, model/version, date, prompt, output, and criterion-level findings.