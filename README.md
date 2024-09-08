# Online-News-Popularity-Prediction
This project aims to predict the popularity of online news articles using various machine learning models. By analyzing factors such as the number of hyperlinks, keywords, and images, we can determine how these attributes influence the number of shares an article will receive. The dataset used in this project is sourced from the UCI Machine Learning Repository and contains over 39,000 records with 58 predictive features.

**Project Overview**
Objective: To predict the number of shares an article will receive and classify its popularity using machine learning models.
Data Source: UCI Machine Learning Repository
Attributes: The dataset includes 61 attributes, with features like word count, sentiment polarity, and the presence of images/videos.

**Machine Learning Models Used**
Linear Regression: Used for predicting the number of shares.
Logistic Regression: Applied for classifying whether an article will be popular or not.
Support Vector Machines (SVM): Both soft and hard margin SVMs were tested for classification tasks.
Neural Networks: Implemented to model complex relationships and provide higher accuracy for predicting popularity.

**Key Results**
Neural Networks achieved the highest classification accuracy at 98.8%.
Linear Regression with Ridge regularization produced an RMSE of 4285.91 for predicting article shares.
Logistic Regression showed strong classification results with 94.2% accuracy when using log-transformed data.

**Conclusion**
Predicting the popularity of online news articles can help content creators and marketers optimize their strategies. The project’s findings suggest that features such as keywords, number of images, and the subjectivity of the content significantly influence the number of shares an article will receive.

