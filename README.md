# Bias vs Bias – Dawn of Justice: A Fair Fight in Recommendation Systems

This project implements and extends the paper:
"Bias vs Bias – Dawn of Justice: A Fair Fight in Recommendation Systems"

## Main Goal
Investigate whether recommendation systems can become fairer without significantly sacrificing recommendation quality.

## Experiments
- Adaptive Fairness Re-ranking
- Runtime Optimization
- Intersectional Fairness Analysis (Gender × Age)
- Cold-Start Fairness Analysis
- Active vs Inactive User Fairness
- Top-K Robustness Analysis
- Gamma Sensitivity Analysis
- Fairness Generalization Across Demographic Groups

## Requirements
Python 3.10+

pip install pandas numpy scipy scikit-learn matplotlib seaborn jupyter

## Run
1. Open Fairness_Aware_Recsys.ipynb
2. Run all cells sequentially.
3. Review generated plots and evaluation tables.

## Main Results

| Method | HitRate | NDCG | Bias | Runtime |
|----------|----------:|----------:|----------:|----------:|
| Baseline | 0.957 | 0.680 | 0.937 | ~0 |
| Fair Paper Method | 0.955 | 0.676 | 0.916 | 67.94s |
| Adaptive Method | 0.958 | 0.680 | 0.899 | 94.46s |
| Optimized Fair | 0.955 | 0.676 | 0.916 | 1.24s |

## Author
Michael Antoniades
