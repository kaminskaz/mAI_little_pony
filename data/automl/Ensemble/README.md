# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model              |   Weight |
|:-------------------|---------:|
| 3_Default_Xgboost  |        1 |
| 4_Default_CatBoost |        4 |

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.074684 | nan           |
| auc       | 0.996244 | nan           |
| f1        | 0.980344 |   0.622596    |
| accuracy  | 0.974803 |   0.622596    |
| precision | 1        |   0.99416     |
| recall    | 1        |   0.000136718 |
| mcc       | 0.945262 |   0.622596    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.074684 |  nan        |
| auc       | 0.996244 |  nan        |
| f1        | 0.980344 |    0.622596 |
| accuracy  | 0.974803 |    0.622596 |
| precision | 0.98155  |    0.622596 |
| recall    | 0.979141 |    0.622596 |
| mcc       | 0.945262 |    0.622596 |


## Confusion matrix (at threshold=0.622596)
|                           |   Predicted as CONFIRMED |   Predicted as FALSE POSITIVE |
|:--------------------------|-------------------------:|------------------------------:|
| Labeled as CONFIRMED      |                      440 |                            15 |
| Labeled as FALSE POSITIVE |                       17 |                           798 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
