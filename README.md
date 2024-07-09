# IRIS-FLOWER-CLASSIFICATION
My 3rd DataScience Project IRIS-FLOWER-CLASSIFICATION
          IRIS FLOWER CLASSIFICATION
1. The Iris flower dataset consists of three species: setosa, versicolor,
   and virginica. These species can be distinguished based on their
   measurements. Now, imagine that you have the measurements
   of Iris flowers categorized by their respective species. Your
   objective is to train a machine learning model that can learn from
   these measurements and accurately classify the Iris flowers into
   their respective species.
2. Use the Iris dataset to develop a model that can classify iris
   flowers into different species based on their sepal and petal
   measurements. This dataset is widely used for introductory
   classification tasks.

Dataset:- https://www.kaggle.com/datasets/arshid/iris-flower-dataset

### Explanation of the Code:
1. **Data Loading**: Load the Iris dataset.
2. **Data Preprocessing**:
   - Encode the categorical labels (species) using `LabelEncoder`.
3. **Model Building**:
   - Define features (`X`) and target variable (`y`).
   - Split the data into training and testing sets.
   - Train a `RandomForestClassifier` model on the training set.
4. **Model Evaluation**:
   - Make predictions on the test set.
   - Evaluate the model's performance using accuracy, confusion matrix, and classification report.
