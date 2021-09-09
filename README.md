# PCA and classification kidney disease
The project aims to classify kidney disease risk and perform principal component analysis (PCA) based on diagnostic tests.

## PCA steps
1. Autoscaling of variables.
2. PCA and transformation variables to principal components (PC).
3. Plot percentage of described variability of principal component.
4. Projection of objects on the PC1/PC2 plane
5. Plot a heat map showing the charges of the principal components.

## Classification steps
1. Division of data into training and testing set.
2. Application of classifiers with linear, polynomial and radial basis function kernel.
3. Model training.
4. Plot ROC curve for all classifiers.
5. Choose the best classifiers (linear) and determination of model evaluation metrics and confusion matrix.

## Used Technologies 
- Language: Python 
- Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

## How to run
1. Download data from Kaggle [Dataset](https://www.kaggle.com/abhia1999/chronic-kidney-disease?select=new_model.csv)
2. Clone the repository.
3. Use Google Colab or Jupyter Notebooks to run `kidney_disease_classification.ipynb` and `kidney_disease_PCA.ipynb`
