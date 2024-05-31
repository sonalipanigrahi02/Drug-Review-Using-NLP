# Drug Review Prediction Using AI in Healthcare

## Introduction
This project leverages Artificial Intelligence to predict drug review outcomes based on patient reviews. As part of an exploratory data analysis, we used several machine learning techniques to classify medical conditions from drug reviews, highlighting the practical application of AI in healthcare which is projected to be a major industry by 2030.

## Project Overview
The project involves the following components:
- **Data Collection:** Using a dataset with approximately 215,000 reviews which include drug names, conditions, ratings, and patient reviews.
- **Exploratory Data Analysis (EDA):** Visualizations to understand the distribution of ratings, drug usage for conditions like birth control, and correlation among features.
- **NLP and Labels Preprocessing:** Techniques such as stop word removal, stemming, and tokenization were employed to prepare the data for modeling.
- **Modeling:** Implementation of various classification models like Random Forest, KNN Classifiers, Multinomial Naïve Bayes, and SGD Classifiers.
- **Results Analysis:** Evaluation of model performance with metrics such as accuracy and F1 scores.

## Data
The dataset includes:
- Drug name
- Condition (disease)
- Rating
- Patient review
It is split into 75% training and 25% test sets with only 0.55% missing values in the condition column.

## Models and Results
- **Random Forest:** Achieved the highest accuracy of 61% on the training set and 54.14% on the test set.
- **SGD Classifier:** Provided an accuracy of 54%.
- **Multinomial Naïve Bayes and KNN:** Showed lower performance compared to other models.

## Challenges and Solutions
During the project, challenges such as imbalanced data and noisy labels were addressed through techniques like undersampling and advanced label preprocessing using SHAP analysis for feature selection.

## Future Work
- Further sentiment analysis on the drug review dataset.
- Integration of Deep Learning models like LSTMs and Transformers.
- Improvement of NLP preprocessing to enhance model accuracy.

## Technologies Used
- **Languages and Libraries:** Python, R, SQL, scikit-learn, pandas, Matplotlib.
- **Tools:** Jupyter Notebooks, Tableau for visualizations.

## How to Use
1. Clone the repository.
2. Install the required libraries mentioned in `requirements.txt`.
3. Run the Jupyter notebooks to view the analysis and modeling steps.

## Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate.
 
