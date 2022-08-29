# Text_mining_project_repository
 A repository for the text mining project for the course 732A92

## Abstract
We present the performance of different sentiment classification methods for the IMDb movie reviews dataset. We use Logistic Regression (LR), Random Forest Classifier (RF) and Support Vector Machines (SVMs) as baselines and BiLSTM, Bert-base and Albert as advanced neural network models for the purpose of sentiment classification. We find that the BiLSTM offers the best trade-off between computational needs and accuracy. We also find that the models Bert and Albert perform the best as neural methods for the task of sentiment classification but only marginally better than BiLSTM. Finally, we find that the best (baseline) method is SVM (accuracy of 0.9), the least computationally efficient is the SVM and the method that offers the best tradeoff is LR.



## Use

- Please remember to load the .csv files to the Colab session after connecting to runtime
- Some of the cells are commented out to bypass some slow computations
- Recommended to run the cells using Colab Pro and GPU acceleration
- Some computations are very long (8h for SVM grid search)
