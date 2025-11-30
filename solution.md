# Solution

I approached the task by first preprocessing the data, converting non-numeric values into numerical form and creating additional derivative features - rotation index, asymmetry index and deformation index. On the prepared dataset, I trained several classification models: logistic regression, decision tree and random forest, applying standardization only for the logistic regression pipeline. I evaluated all models using accuracy, ROC-AUC, precision-recall curves and confusion matrices, and compared their performance to identify the most effective classifier.
