# kaggle-Competition-Mushroom---Classification
A machine learning classification model that predicts whether a mushroom is edible or not based on its physical characteristics. The project uses categorical feature encoding and ensemble methods like Random Forest to achieve high accuracy. It demonstrates how proper preprocessing significantly improves model performance on structured datasets.



🍄 Mushroom Classification Model



📌 Overview

This project focuses on building a machine learning classification model to predict whether a mushroom is edible (e) or poisonous (p) based on its physical characteristics.

The dataset used is a well-known benchmark in machine learning, containing detailed categorical features such as cap shape, gill color, odor, and habitat.

📊 Dataset Information
Total Samples: 8,124
Features: 24 categorical attributes
Target Variable:
e → Edible
p → Poisonous

All features are categorical and required preprocessing before model training.

⚙️ Methodology


🔹 Data Preprocessing

Handled categorical variables using One-Hot Encoding
Combined train and test datasets to ensure consistent feature encoding
Encoded target labels using Label Encoding


🔹 Model Building

Multiple machine learning models were explored:

Decision Tree (Baseline)
Random Forest (Improved Model)

The Random Forest Classifier was selected as the final model due to its superior performance on categorical data.

🔹 Training Strategy


Split dataset into training and validation sets
Trained model using ensemble learning techniques
Evaluated performance using accuracy score




📈 Results
Achieved high classification accuracy (≈ 98–100%)
Demonstrates strong separability in the dataset



💡 Key Insights
Certain features (like odor) are highly predictive of mushroom toxicity
Tree-based models perform exceptionally well on categorical datasets
Proper encoding significantly improves model performance



📦 Output
The final predictions are stored in a submission.csv file in the required format:

id,class
0,e
1,p
...
🚀 Future Improvements
Implement advanced models like XGBoost / LightGBM
Perform feature importance analysis
Add visualization for better interpretability
🛠️ Tech Stack
Python
Pandas
Scikit-learn
📎 Conclusion

This project demonstrates how proper preprocessing and ensemble learning techniques can achieve near-perfect accuracy on structured categorical datasets.
