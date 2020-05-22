Exploring the Housing Market in Ames, Iowa:

This project poses two questions, one as a regression task and the other as a classification task, and attempts to answer them based on the freely available Ames, Iowa data set available on Kaggle at https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview.

Regression Task:  How accurately can we classify whether a house is of high or low quality based on quantitative and qualitative descriptions of its features?

The RealEstateRegression notebook examines this task, implementing Linear Regression (with and without regularization to deal with high dimensionality), K-Nearest Neighbors, and Extreme Gradient Boosting (XGBoost, an optimized ensemble tree method that builds and learns sequentially, making adjustments based on the residuals of previous weak learners). 

Classification Task:  How accurately can we predict house prices based on quantitative and qualitative descriptions of its features?

The RealEstateClassification notebook shows data processing and modeling to answer this classification problem.  Single models attempted were Decision Trees, Logistic Regression (with and without regularization), and a Support Vector Machine.  Ensemble methods included a Hard and Soft Voting classifier (with the best Tree, Logistic Regression, and Support Vector Machine), and Random Forest. 

Additional Files:

Included in this repository is a file showing data imports and preprocessing (RealEstateKaggleNotebook.ipynb), in addition to the previously mentioned task-specific notebooks, RealEstateClassification.ipynb and RealEstateRegression.ipynb.  The slides for the presentation of results are also included.  A Flask app is in development and will be included when complete.

