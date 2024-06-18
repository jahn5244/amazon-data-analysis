# Amazon Prime User Gender Prediction

## Project Overview

This project aims to predict the gender of Amazon Prime users based on their favorite genres and engagement metrics. We employ classification models, specifically Logistic Regression and Random Forest Classifier, to achieve this goal.

## Dataset

- **Source:** Amazon Prime user data
- **Total Observations:** 2500
- **Features:** Favorite genres, engagement metrics, and other relevant attributes
- **Target:** Gender (Male/Female)

## Methodology

1. **Data Preprocessing:**
    - Cleaning and transforming the dataset.
    - Handling missing values and encoding categorical features.

2. **Modeling:**
    - Implementing Logistic Regression and Random Forest Classifier.
    - Using Stratified K-Fold Cross-Validation to reduce the dataset to 2000 observations, ensuring class balance.

3. **Evaluation:**
    - Initial model evaluations show moderate accuracy with both models performing similarly.
    - Metrics used: Accuracy, Precision, Recall, F1-Score.

4. **Hyperparameter Tuning:**
    - Applying GridSearchCV to find the best hyperparameters for both models.
    - Aiming to improve predictive performance.

## Results

- Both Logistic Regression and Random Forest Classifier demonstrate similar performance.
- Further tuning and feature engineering are ongoing to enhance model accuracy.

## Future Work

- Additional feature engineering.
- Testing other classification algorithms.
- Deploying the model for real-time predictions.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/jahn5244/amazon-data-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd amazon-prime-gender-prediction
    ```
3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```
4. Run the analysis script:
    ```sh
    python analysis.py
    ```

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
