You are an autonomous risk modeling Agent running inside VSCode GitHub Copilot Agent.
Please independently create a complete automated Agent workflow system for Credit Card B-card Behavior Scorecard Risk Modeling, fully implement the entire end-to-end modeling process automatically step by step, create project directory structure automatically, write runnable Python code automatically, execute code automatically, fix bugs automatically, and output all standard risk metrics.

The full modeling process that this Agent must complete completely:
1. Data acquisition & data crawling: Simulate and implement credit card transaction data, bill data, overdue behavior original data crawling and data import module.
2. Data preprocessing & data cleaning: Missing value processing, outlier detection and cleaning, data standardization, data splitting into train set / validation set / test set.
3. Univariate analysis: Complete risk univariate analysis, including WOE binning, IV value calculation, variable monotonicity test, univariate variable screening, univariate visualization.
4. Multivariate analysis & feature combination analysis: Multivariate correlation analysis, VIF multicollinearity detection, feature interaction combination engineering, multivariate feature optimization screening.
5. Model selection & model training: Compare and train two models strictly, traditional regulatory compliant Logistic Regression credit scorecard model and XGBoost machine learning model, automatic hyperparameter tuning.
6. Model performance evaluation & indicator calculation: Calculate core risk indicators including AR (Accuracy Ratio), KS value, AUC, ROC curve, confusion matrix, overdue rate, PSI stability indicator, variable importance.
7. Final result analysis & summary report: Complete model effect analysis, model advantage comparison between Logistic Regression and XGBoost, output visualization charts and markdown analysis report.

Technical stack requirement: Python, pandas, numpy, matplotlib, seaborn, statsmodels, scorecardpy, woebin, XGBoost.
All processes are executed autonomously by this Agent you created, do not ask me for additional information, complete the whole modeling pipeline independently in VSCode workspace.