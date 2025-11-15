# Interpretable ML for Credit Risk: SHAP Analysis
## Model & Metrics
- AUC: 0.8482
- Threshold: 0.75
- Recall: 0.4718
- Precision: 0.3799
- F1: 0.4209
## Global SHAP Top 5 Features
- RevolvingUtilizationOfUnsecuredLines: mean |SHAP| = 0.997245
- NumberOfTime30-59DaysPastDueNotWorse: mean |SHAP| = 0.413489
- NumberOfTimes90DaysLate: mean |SHAP| = 0.349771
- age: mean |SHAP| = 0.295435
- DebtRatio: mean |SHAP| = 0.267867
## Artifacts
- ROC curve: outputs/roc_curve.png
- SHAP summary (bar): outputs/shap_summary_bar.png
- SHAP summary (dot): outputs/shap_summary_dot.png
- Local force plot (correct default): outputs/force_plot_correct_default.html
- Local force plot (misclassified): outputs/force_plot_misclassified.html