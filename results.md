### Models Performance Summary

| Model                       | RMSLE on Test Set (All Related Features) | RMSLE on Test Set (Dropped Highly Correlated) | RMSLE on Test Set (Dropped Engineered Features) |
|-----------------------------|------------------------------------------|----------------------------------------|--------------------------------------------------|
| Linear Regression (baseline)| 0.3570                                  | 0.3692                                 | 0.3817                                           |
| Ridge Regression            | 0.3568                                  | 0.3689                                 | 0.3816                                           |
| Lasso Regression            | 0.3564                                  | 0.3685                                 | 0.3815                                           |
| Random Forest               | 0.3275                                  | 0.3336                                 | 0.3320                                           |
| Gradient Boosting           | 0.3381                                  | 0.3462                                 | 0.3483                                           |
| XGBoost                     | 0.2902                                  | 0.3209                                 | 0.3112                                           |
| LightGBM                    | 0.2853                                  | 0.3217                                 | 0.3160                                           |
