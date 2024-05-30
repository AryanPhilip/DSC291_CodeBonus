# DSC291_CodeBonus
Evaluating the Datasets mentioned in the paper

### Comparison of Model Performance on AdvGLUE Test Set

| Model           | SST-2 | MNLI   | RTE   | QNLI  | QQP    | Avg  |
|-----------------|-------|--------|-------|-------|--------|------|
| BERT (Large)    | 33.03 | 28.72  | 40.46 | 39.77 | 37.91  | 33.68 |
| ELECTRA (Large) | 58.59 | 14.62  | 23.03 | 57.54 | 61.37  | 41.69 |
| RoBERTa (Large) | 58.52 | 50.78  | 45.39 | 52.48 | 57.11  | 50.21 |
| T5 (Large)      | 60.56 | 48.43  | 62.83 | 57.64 | 63.03  | 56.82 |
| ALBERT (XXLarge)| 66.83 | 51.84  | 73.03 | 63.84 | 56.40  | 59.22 |
| DeBERTa (Large) | 57.89 | 58.36  | 78.95 | 57.85 | 60.43  | 60.86 |
| **GPT-3.5**     | 62.84 | 59.60  | 48.15 | 51.35 | 63.49  | 57.49 |


The **GPT-3.5** model shows competitive performance across various tasks, with notable strengths in MNLI and QQP tasks, achieving an average score of 57.49. This is close to the top-performing model, DeBERTa (Large), which has an average score of 60.86.
