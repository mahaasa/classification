# classification
 Classification Project
This project involves the classification using various machine learning models. The goal is to predict the class of stars based on several features using a combination of traditional machine learning models, ensemble methods, and deep learning techniques.

Project Structure
The project is organized as follows:

Data Import and Preprocessing (0-import.txt, 1-preprocessing.txt):

The dataset is imported and preprocessed. This includes encoding categorical variables, splitting the data into training and testing sets, and scaling the features. Special transformations are applied to prepare data for LSTM and Transformer models.
Model Implementations:

Logistic Regression
Decision Tree (3-Decision tree.txt): A Decision Tree Classifier is trained and evaluated.
Random Forest (4-Random Forest.txt): A Random Forest Classifier is trained and evaluated.
CatBoost
XGBoost (6-XGBoost.txt): An XGBoost model is trained and evaluated.
LSTM (12-LSTM.txt): A custom LSTM model is implemented, trained, and evaluated.
Transformer (13-Transformer Model.txt): A Transformer model is implemented, trained, and evaluated.
Voting Classifier (14-voting.txt): An ensemble model using Voting Classifier is created, combining Decision Tree, XGBoost, CatBoost, and Random Forest.
Evaluation and Results (15-result.txt, 16-ROC.txt):

The performance of each model is evaluated using metrics such as accuracy, F1-score, precision, recall, sensitivity, and specificity.
ROC curves are plotted to compare the performance of different models.
Requirements
To run the code, you need to have the following Python packages installed:

bash
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn xgboost catboost tensorflow
How to Run the Project
Preprocessing:

Run the preprocessing script to prepare the dataset.
Model Training:

Each model can be trained by running the corresponding script (e.g., 3-Decision tree.txt for the Decision Tree model).
Evaluation:

After training, the models can be evaluated using the provided metrics and the results can be compared.
ROC Curves:

The ROC curves can be plotted to visually compare the performance of the models.
Results
The results of the models are stored in a DataFrame and can be saved as a CSV file for further analysis.

Conclusion
This project demonstrates the application of various machine learning and deep learning models for star classification. The results show that ensemble methods and deep learning models like LSTM and Transformer can significantly improve classification accuracy.
