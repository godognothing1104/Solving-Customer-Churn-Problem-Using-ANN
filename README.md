# ANN for Customer Churn Prediction

This project demonstrates the creation and training of an Artificial Neural Network (ANN) to predict customer churn based on a structured dataset. The model is built using Python, TensorFlow, and various preprocessing techniques.

## Features

- Data preprocessing, including:
  - Encoding categorical data (Gender and Geography columns).
  - Standardizing numerical features.
- Building a sequential ANN using TensorFlow with:
  - Input and hidden layers with ReLU activation.
  - Output layer with sigmoid activation for binary classification.
- Model training and evaluation, including:
  - Model compilation with the Adam optimizer and Binary Crossentropy loss.
  - Training the model with performance metrics.
  - Generating predictions on test data.
  - Evaluation using confusion matrix and accuracy score.

## Installation

1. Clone the repository or download the project files.
2. Install the required dependencies using the following command:

   ```bash
   pip install -r requirements.txt
   ```

Ensure that you have Python 3.8+ and a compatible version of TensorFlow installed as per your system configuration.

## Dataset

The project uses external data located in `data/Churn_Modelling.csv`. Ensure the file structure remains consistent with the code, and the dataset adheres to the structure required by the process (e.g., the target variable is in the last column, and the features are properly aligned).

## How to Run

1. Install the dependencies as described.
2. Place the dataset at the specified location (`data/Churn_Modelling.csv`).
3. Open the Jupyter Notebook or run the script as desired.
4. Follow the steps in the code to preprocess the data, build the ANN, and train the model.

## Libraries Used

The following libraries are used to build the project:

- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and preprocessing.
- **TensorFlow**: For building and training the Artificial Neural Network.
- **Scikit-learn**: For preprocessing, splitting the dataset, and evaluating the model.

## Results

Upon completion of training, the model predicts customer churn with the given test data. The accuracy and performance metrics are displayed at the end.

## Note

This project assumes basic knowledge of Python and Machine Learning. Ensure all dependencies are installed before running the code.

## License

This project is for educational purposes and is provided without any warranty. Use at your own discretion.