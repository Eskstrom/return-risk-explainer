# Return-Risk Explainer

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=product-service-design#library)

## Product brief

A listing-quality assistant that identifies product-information gaps likely to cause preventable returns, such as compatibility ambiguity, missing dimensions, or unclear specifications.

## Design focus

Explain ambiguous product information without claiming proven return reduction.

## Proposed scope

- Synthetic product listings with known information-quality issues.
- Rule-based risk flags and an explainable score.
- Suggested copy/attribute improvements.
- Comparison view showing listing quality before and after changes.

## Validation targets

- Every risk flag points to specific missing or conflicting information.
- No unsupported claim that the tool predicts real-world return rates.

## Potential implementation

TypeScript or Python, React/Streamlit, SQLite.

## Guardrails

Position it as a decision-support prototype, not a deployed risk model.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)
