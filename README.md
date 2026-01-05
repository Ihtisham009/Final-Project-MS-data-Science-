
# Predicting Subjective Health/Daily Wellbeing from Socioeconomic and Demographic Data

This project focuses on predicting subjective health and daily wellbeing based on socioeconomic and demographic data, such as age, gender, income, and other clinical indicators. The goal is to explore how machine learning models can predict individual wellbeing scores, leveraging various socioeconomic and demographic features.

## **Research Questions**
1. Can machine learning models accurately predict subjective health and daily wellbeing using socioeconomic and demographic data?
2. Which socioeconomic and clinical factors have the most significant impact on an individual's subjective wellbeing score?
3. How can we address challenges such as class imbalance and feature interpretation in predicting wellbeing?

## **Dataset Details**
- **Name:** Wellbeing and Socioeconomic Data
- **Source:** The dataset includes clinical and demographic data, including wellbeing scores, age, gender, and other clinical health features.
- **Contributors:** This dataset was designed to explore how various factors influence subjective wellbeing.

## **Libraries Used**
- **pandas** for data manipulation
- **matplotlib** and **seaborn** for data visualization
- **numpy** for numerical operations
- **scikit-learn** for machine learning models and metrics
- **SHAP** for model interpretability and feature importance analysis

## **Steps Performed in the Notebook**
1. **Importing Libraries:** The necessary libraries for data manipulation, model building, and evaluation are imported.
2. **Reading the Dataset:** The dataset is loaded and initial insights are provided through descriptive statistics and visualizations.
3. **Data Preprocessing:** Missing values are handled, features are scaled for model training, and unnecessary columns are removed.
4. **Feature Engineering:** Features like socioeconomic data (e.g., age, gender) and clinical data (e.g., heart rate) are selected for model training.
5. **Model Training:** Machine learning models, including Logistic Regression, KNN, and Gaussian Naive Bayes, are trained to predict wellbeing scores.
6. **Hyperparameter Optimization:** Models are optimized using RandomizedSearchCV to find the best parameters for each model.
7. **Model Evaluation:** The models are evaluated using accuracy, precision, recall, and F1-score, with comparisons drawn between the different models.
8. **SHAP Analysis:** SHAP values are used to interpret the model results and understand which features contribute most to the wellbeing score predictions.

## **How to Run the Notebook**
1. Clone the repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn numpy scikit-learn shap
   ```
3. Download the dataset (Wellbeing and Socioeconomic Data) and upload it to the appropriate location.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Execute all the cells to perform the analysis and model training.

## **Results**
This project aims to predict subjective health and daily wellbeing using machine learning models and to identify which demographic and socioeconomic factors influence subjective health outcomes.

## **Contributions**
Feel free to contribute by:
- Adding new machine learning models.
- Improving feature engineering techniques.
- Enhancing model interpretability.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
