# FMPlayerDevModel
The most comprehensive study on player development in Football Manager yet, taking advantage of interpretable machine learning methods in a very large dataset, allowing us to draw conclusions regarding how each variable affects player development.

The Data Treatment notebook receives data already worked on google sheets and does a final treatment (namely exact player age), creating several datasets, I use GKFlagMarginData.

Model Training NN includes a Neural Network approach that was scrapped for performing slightly worse than XGBoost and being harder to interpret.

LRXG has a linear regression implementation (performs poorly as expected) and the XGBoost implementation used for the final model.

Full details can be seen in: https://www.youtube.com/watch?v=LMCzpFM4tns


