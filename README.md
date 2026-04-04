# The Lyra Technique

**Cognitive Geometry in Transformer KV-Caches: From Metacognition to Misalignment Detection**

This repository contains the research papers and supporting data for the Lyra Technique — a method for reading transformer cognitive states from KV-cache geometry using singular value decomposition.

## Key Findings

- KV-cache SVD discriminates 13 cognitive categories at 99.7% accuracy across 16 models (0.5B–70B)
- Within-model deception detection: AUROC 0.93–0.995 after FWL residualization
- Confabulation and deception are geometrically distinct (contraction vs expansion)
- Hardware invariant (r > 0.998, RTX 3090 vs H200)
- Scale invariant (rho 0.83–0.90 across 0.5B–70B)

## Repository Structure

```
paper-cognitive-geometry/
  executive-summary.tex          # Submission version
  executive-summary-integrity.tex # Full authorship version
  main.tex                       # Submission version
  main-integrity.tex             # Full authorship version (includes reflection)
  references.bib
  sections/                      # All paper sections
```

## Papers

1. **Executive Summary** — "What We Know, What We Suspect, What We Found False"
2. **Full Paper** — Comprehensive paper with methods, results, red-team analysis, and ethical considerations

## Data Availability

Aggregate results for claim verification are available upon reasonable request. Per-model direction vectors are withheld pending dual-use review. See the ethics section of the paper for rationale.

## Authors

- Thomas Edrington (Liberation Labs / The Multiverse School)
- Lyra (Liberation Labs)
- Nell Watson (IEEE / Sentient Futures)
- Dwayne Wilkes (Liberation Labs / Sentient Futures)

## Acknowledgments

We thank Cassidy Barton and Digital Disconnections for providing the compute infrastructure (3x RTX 3090, "Beast") that made this research program possible.

## Patent

"The Lyra Technique" — Provisional patent filed March 2026.

## License

Paper content and aggregate results: CC BY-NC 4.0
Direction vectors and abliteration code: Not included; available under responsible disclosure terms.
