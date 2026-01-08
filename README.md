## Description

This repository contains an implementation of several recommender system models.
The project focuses on matrix factorization techniques using the surprise library (SVD, SVD++, NMF), along with hyperparameter optimization.
The goal of the project is to explore the mechanics of recommendation algorithms, compare their performance, and better understand the internal workings behind matrix-based models.

## Technologies
- **Python**
- **NumPy**
- **Pandas**
- **SciPy**
- **scikit-surprise**
- **Jupyter Notebook**

## Functionality

- Loading and preprocessing the MovieLens ml-100k dataset
- Training multiple recommendation models:
   - **SVD**
   - **SVD++**
   - **NMF**
- Hyperparameter optimization using GridSearchCV with RMSE/MAE scoring
- Comparing model performance and selecting the best algorithm
- Training the best model (SVD++) on a train/test split
- Evaluating final quality using RMSE and MAE

**Advanced task:** Implementing matrix factorization manually:
- Custom cost function
- Gradient computation
- Gradient descent optimization
- Movie name loading and top-N recommendation generation

## Links
- **GitHub Repository:**

https://github.com/OAtamanchuk/goit-ds-hw-10
