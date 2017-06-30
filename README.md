# Breast cancer biopsy diagnosis using SVM classifier

Workbook looking at using support vector machine to predict biopsy classifications using the UCI Wisconsin breast cancer  dataset.

We used Scikit Learn's gridsearch to optimise C and gamma hyperparameters for margin and rbf effect.  

The classification works well with only 5% misclassifications, however the recall for malignant class could do with improving so that malignants are not classed as benign.  

Options for further work to revisit and improve:

- Look at the second and third best gridsearch outcomes. Do either of these give better recall? 
- Scale features
