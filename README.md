# Titanic-Kaggle-Challenge
## Project Structure

### 1. Data Loading and Exploration
   - Utilizes Pandas to load the Titanic dataset (`train.csv` and `test.csv`) and explores the structure of the input data.

### 2. Data Preprocessing
   - Extracts relevant features ('Pclass', 'Sex', 'Parch') for model training.
   - Handles missing values in the training data.
   - Splits the data into training and validation sets.

### 3. Categorical Encoding
   - Applies Target Encoding to categorical features ('Pclass', 'Sex', 'Parch') using the Category Encoders library.

### 4. Model Development
   - Implements a RandomForestClassifier using Scikit-learn.
   - Utilizes a pipeline to handle missing values and train the model.
   - Performs hyperparameter tuning using GridSearchCV to find the best combination of parameters.

### 5. Model Evaluation
   - Assesses the performance of the model on the validation set using metrics such as accuracy, confusion matrix, and classification report.

### 6. Prediction on Test Data
   - Applies the trained model to the test dataset to predict the survival status of passengers.

## Usage
1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd Titanic-Survival-Prediction`
3. Include the `test.csv` and `train.csv` datasets in the project root directory.
4. Run the Jupyter notebook or Python script to execute the complete workflow.

Feel free to explore, modify, and contribute to this project to enhance its functionality and performance. Your feedback and contributions are highly appreciated!

**Note:** Ensure that the `test.csv` and `train.csv` datasets are present in the project root directory before running the notebook or script.
