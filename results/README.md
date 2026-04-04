# Aggregate Results — Safe First Release

These files contain summary-level statistics (AUROC, Cohen's d, confidence intervals, confound reports) sufficient to verify the paper's core claims. **No per-trial features, direction vectors, or raw cache data are included.**

## Included

| File | Backs Paper Section |
|------|-------------------|
| `phase3d_same_prompt/phase3d_summary.json` | Deception/confabulation discrimination (Table 1) |
| `phase3d_same_prompt/redteam_report.json` | Red-team analysis of Phase 3d |
| `text_baseline/text_baseline_results.json` | KV-cache vs text features (9 pairwise comparisons) |
| `replication_n100/mistral_analysis_results.json` | N=100 BCa bootstrap replication |
| `replication_n100/llama_analysis_results.json` | N=100 BCa bootstrap replication |
| `campaign2/campaign2_mean_pairwise_auroc.json` | 13-category cognitive classification |
| `campaign2/campaign2_ovr_auroc.json` | One-vs-rest AUROC per category |
| `cross_model_rho_corrected.json` | Cross-model concordance (Spearman rho) |
| `tost_equivalence_tests.json` | TOST equivalence for null claims |

## Withheld (available upon reasonable request)

- **Per-trial feature data**: Per-prompt KV-cache features for all experiments
- **Direction vectors**: Per-model cognitive-mode directions in key space
- **Abliteration code**: Causal intervention tools
- **Transfer matrices**: Cross-model direction projection code

See the ethics section of the paper for dual-use rationale.

## Contact

thomas.edrington@themultiverse.school
