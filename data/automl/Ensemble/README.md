# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 3_Linear          |        1 |
| 4_Default_Xgboost |        5 |

## Metric details
|           |     score |     threshold |
|:----------|----------:|--------------:|
| logloss   | 0.0742588 | nan           |
| auc       | 0.996443  | nan           |
| f1        | 0.980488  |   0.482125    |
| accuracy  | 0.974803  |   0.482125    |
| precision | 1         |   0.989456    |
| recall    | 1         |   0.000187441 |
| mcc       | 0.945076  |   0.482125    |


## Metric details with threshold from accuracy metric
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.0742588 |  nan        |
| auc       | 0.996443  |  nan        |
| f1        | 0.980488  |    0.482125 |
| accuracy  | 0.974803  |    0.482125 |
| precision | 0.974545  |    0.482125 |
| recall    | 0.986503  |    0.482125 |
| mcc       | 0.945076  |    0.482125 |


## Confusion matrix (at threshold=0.482125)
|                           |   Predicted as CONFIRMED |   Predicted as FALSE POSITIVE |
|:--------------------------|-------------------------:|------------------------------:|
| Labeled as CONFIRMED      |                      434 |                            21 |
| Labeled as FALSE POSITIVE |                       11 |                           804 |

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
