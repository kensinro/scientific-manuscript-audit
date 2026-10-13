# Synthetic manuscript audit: illustrative demonstration

**DEMONSTRATION ONLY.** Fictional case with no real client, study data, automated-system validation, or manuscript submission.

## Scenario
A hypothetical treatment-response classifier uses 80 invented records (40 positive, 40 negative) and reports held-out accuracy 0.83 on one internal split. Its abstract says “clinically validated” and “first of its kind.” There is no external validation, calibration, confidence interval, documented search protocol, or fair baseline comparison. A sample table inconsistently reports 0.82.

## Example audit findings
| ID | Observation | Priority | Action |
|---|---|---|---|
| S01 | Internal accuracy does not establish clinical validity | High | Narrow claim; plan external validation |
| S02 | Uncertainty, class-level diagnostics and calibration missing | High | Report confusion matrix, uncertainty and diagnostic metrics |
| S03 | Comparator is inadequately specified | High | Match evaluation conditions and document fair baselines |
| S04 | “First of its kind” is unsubstantiated | Medium | Conduct dated literature review and qualify novelty |
| S05 | 0.83 versus 0.82 conflict | Medium | Reconcile numerator, denominator, rounding and source files |

## Claim–evidence matrix
| Claim | Available evidence | Supported wording |
|---|---|---|
| Clinically validated | One internal split | Internal performance only; no clinical validation established |
| First approach | No documented literature search | Novelty **not verified** |
| Generalizes robustly | No independent external cohort | Generalization **not established** |

## Suggested revisions
1. Bound conclusions to what is demonstrated.
2. Document split provenance, leakage controls and uncertainty.
3. Use credible, reproducible comparator designs.
4. Record literature search scope before novelty claims.
5. Align abstract, figures, tables and supplements.

**Scope limitation:** This is a writing sample demonstrating review style, not evidence of audit-tool accuracy, detection rate, model performance, or guaranteed journal acceptance.