# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **num_class**: 4
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

0.8 seconds

### Metric details
|           |   Black/African American |   Multi-racial |   Other Race |       White |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|-------------------------:|---------------:|-------------:|------------:|-----------:|------------:|---------------:|----------:|
| precision |                        0 |              0 |            0 |    0.569426 |   0.569426 |    0.142356 |       0.324246 |   1.02122 |
| recall    |                        0 |              0 |            0 |    1        |   0.569426 |    0.25     |       0.569426 |   1.02122 |
| f1-score  |                        0 |              0 |            0 |    0.725648 |   0.569426 |    0.181412 |       0.413203 |   1.02122 |
| support   |                      843 |             45 |         1016 | 2518        |   0.569426 | 4422        |    4422        |   1.02122 |


## Confusion matrix
|                                   |   Predicted as Black/African American |   Predicted as Multi-racial |   Predicted as Other Race |   Predicted as White |
|:----------------------------------|--------------------------------------:|----------------------------:|--------------------------:|---------------------:|
| Labeled as Black/African American |                                     0 |                           0 |                         0 |                  843 |
| Labeled as Multi-racial           |                                     0 |                           0 |                         0 |                   45 |
| Labeled as Other Race             |                                     0 |                           0 |                         0 |                 1016 |
| Labeled as White                  |                                     0 |                           0 |                         0 |                 2518 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
