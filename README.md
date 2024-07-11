# credit-card-fraud-detection
DSC540 - Advanced Machine Learning course

# Credit Card Fraud Detection

## Author
- **Jashwanth Neeli**
- DePaul University

## Abstract
With the rise of digital banking, credit card transactions have increased exponentially, as have fraudulent activities. This project aims to leverage machine learning models to detect and predict fraudulent transactions in real-time, thereby enhancing security measures and maintaining customer trust.

## Introduction
The financial sector's shift to digital technology has improved transaction convenience and efficiency but has also increased exposure to fraud. This project uses advanced machine learning techniques to address the challenge of credit card fraud, focusing on minimizing the risk and associated costs.

## Dataset
The dataset, sourced from Kaggle, consists of 284,807 credit card transactions from European cardholders in September 2013, with 492 (0.172%) fraudulent transactions. It features anonymized PCA-transformed variables labeled V1 through V28, along with 'Time' and 'Amount' variables. The dataset's severe class imbalance is addressed with techniques like Random Oversampling and SMOTE.

## Methodology
- **Data Analysis:** Initial data exploration was conducted to understand the structure and attributes, with no missing values detected. Data distribution was visualized using density plots to differentiate between fraudulent and non-fraudulent transactions.
- **Model Training:** Various machine learning models, including Decision Trees, Random Forests, and XGBoost, were trained on the dataset. Performance was evaluated using metrics like ROC-AUC, Precision, Recall, and F1-Score.
- **Class Imbalance:** Addressed using Random Oversampling and SMOTE to balance the dataset and improve model sensitivity to fraudulent transactions.

## Results
Models trained on balanced datasets showed improved performance across all metrics compared to those trained on unbalanced data. XGBoost demonstrated superior capability in handling class imbalances and generalizing to new data.
![image](https://github.com/jashwanthneeli/credit-card-fraud-detection/assets/76511089/2430236c-078c-4cb4-9bfa-d42753012f4e)

## Challenges and Future Work
- **Overfitting:** Noted in Decision Tree models, suggesting the need for regularization techniques.
- **Class Imbalance:** Continued exploration of advanced sampling methods and cost-sensitive learning is recommended.
- **Hyperparameter Tuning:** To enhance model performance, further optimization of model parameters is necessary.

## Conclusion
This project highlights the significance of addressing class imbalance and the choice of appropriate machine learning models for effective credit card fraud detection. Future efforts will focus on refining models and techniques to further enhance the detection capabilities.

## References
- Andrea Dal Pozzolo, et al. "Calibrating Probability with Undersampling for Unbalanced Classification," CIDM, IEEE, 2015.
- [More References](https://www.researchgate.net/publication/283349138_Calibrating_Probability_with_Undersampling_for_Unbalanced_Classification)

