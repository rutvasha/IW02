# Project Summary

This project focuses on analyzing and predicting song popularity by leveraging regression techniques and emotional data. The notebooks cover tasks such as sentiment analysis, data preprocessing, and trend extrapolation, aiming to uncover the relationship between emotional patterns in music and its popularity.

### Notebooks

#### `data_transform.ipynb`
This notebook integrates lyrical and Spotify metadata to analyze the relationship between emotional trajectories in song lyrics and commercial popularity. It includes comprehensive data cleaning (handling missing values/duplicates, text standardization), EDA, and feature engineering (segmenting lyrics and generating emotion values per index). 

#### `data_extrapolation.ipynb`
This notebook focuses on clustering techniques to uncover patterns in lyrical and metadata-driven song features.Multiple clustering methods, including k-means and agglomerative clustering with DTW, are used to group songs based on emotional trajectories and genre-specific characteristics. Visualizations help interpret cluster results.

#### `base_regressions.ipynb`
This notebook focuses on baseline regression analysis to explore relationships between lyrical, audio, and metadata features and song popularity. It includes data preprocessing, feature selection, and fitting multiple regression models. Model performance is evaluated using metrics such as R-squared and MSE.

#### `sentiment_regressions.ipynb`
This notebook implements advanced regression techniques to predict song popularity using sentiment-based and metadata features. It builds on baseline models by incorporating machine learning methods such as Random Forest, SVR, XGBoost, and regularized regressions (Ridge, Lasso). Hyperparameter tuning is used to optimize model performance. Results are evaluated using metrics like R-squared and MSE.
