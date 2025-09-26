
# Baseline Model Report

## Model Performance
- **Algorithm**: Logistic Regression with balanced class weights
- **Training Time**: 1.05 seconds
- **ROC-AUC Score**: 0.972

## Business Metrics
- **False Positives**: 1,386 (customers incorrectly blocked)
- **False Negatives**: 8 (frauds missed)
- **Estimated Loss**: $14,660

## Key Insights
- The model catches 91.8% of fraud cases
- 2.44% of legitimate transactions are incorrectly flagged
- Each false negative costs ~10x more than a false positive

## Next Steps
- Improve feature engineering
- Try more sophisticated algorithms
- Optimize the decision threshold
