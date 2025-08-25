# Phone-Kart

Technologies: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Machine Learning, Linear Regression, Random Forest, Gradient Boosting


# Objective

The Phone Kart project is designed to develop a machine learning-based predictive system capable of classifying mobile phones into specific price categories based on their technical specifications. The primary aim is to assist online marketplaces, retailers, and customers in estimating the appropriate price range for a given phone configuration.


# Problem Statement

The mobile phone market is highly dynamic, with prices influenced by technical specifications, brand value, and competitive trends. For both customers and retailers, it is often challenging to estimate a fair price based on features such as RAM, storage, camera quality, battery power, and processor speed. Traditional methods of price estimation are largely heuristic and inconsistent.

The Mobile Phone Price Prediction System aims to leverage machine learning models to automatically classify or predict the price range of smartphones based on their specifications. This can help manufacturers in market analysis, retailers in pricing strategy, and consumers in making informed purchase decisions. The challenge lies in capturing the complex relationship between features and market-driven pricing to ensure robust and reliable predictions.


# Solution

Developed a regression-based machine learning model to predict mobile phone prices based on technical specifications such as RAM, storage, battery capacity, camera quality, and screen size. Conducted thorough data cleaning, feature engineering, and exploratory data analysis to identify key price-driving features. Trained models including Linear Regression, Random Forest, and Gradient Boosting, achieving an R² score of over 0.90 using Random Forest Regressor. Optimized model performance through hyperparameter tuning and cross-validation. Visualized prediction trends and feature importances to enhance interpretability.


# Insights & Observations

Ensemble methods like Random Forest and Gradient Boosting are better suited for categorical price prediction than simple regression models.

Linear Regression – Used as a baseline regression model to predict price categories.

Random Forest Classifier – A robust ensemble learning method using bagging of decision trees.

Gradient Boosting Classifier – A boosting approach that sequentially builds strong learners.

Feature scaling improves the performance of models sensitive to feature magnitude.

RAM size is consistently the top predictor of a mobile’s price category.


# Future Scope

Enhancements to the current project may include:

Adding more high-level features such as brand, release year, and operating system.

Using deep learning approaches for feature extraction and classification.

Deploying the model as an API for integration with e-commerce platforms.

Performing hyperparameter optimization for all models to further improve accuracy.


# Conclusion

The Phone Kart project successfully showcased how machine learning models can predict mobile phone price categories based on their specifications. Gradient Boosting emerged as the best-performing model in this study, offering strong predictive accuracy. With further refinements and feature expansion, this system can be deployed in real-world applications to aid buyers and sellers.
