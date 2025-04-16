
# Loan Approval Prediction with Explainable AI

This project demonstrates how to build a machine learning model (Random Forest) to predict loan approval decisions. This model's interpretability is enhanced using the explainable AI (XAI) techniques LIME and Anchor explanations.

## Project Overview

The objective is to create a predictive model that can classify whether a loan application is approved. I use a Random Forest classifier and apply LIME and Anchor to interpret and visualize the model's predictions.

## Dataset

- **Source**: [Loan Approval Classification Dataset - Kaggle](https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data)
- **Format**: CSV
- **Description**: Includes several features such as income, credit history, loan amount, and applicant information to predict loan approval (`loan_status`).

## Technologies Used

| Tool / Library     | Purpose                                        |
|--------------------|------------------------------------------------|
| Python             | Programming language                           |
| pandas / numpy     | Data manipulation                              |
| matplotlib         | Data visualization                             |
| scikit-learn       | Machine learning model and evaluation          |
| LIME               | Local Interpretable Model-agnostic Explanations|
| Alibi (Anchor)     | Rule-based model explanations                  |

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/IvaylaSt/xai_project.git
cd xai-project
```

### 2. Install Dependencies

Use pip to install the required libraries:

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open the Jupyter notebook:

```bash
jupyter notebook xai.ipynb
```

## Notebook Breakdown

- **Data Analysis**: Loads and explores the data.
- **Data Preprocessing**: Encodes categorical variables, splits the data into train-test sets.
- **Random Forest**: Builds a Random Forest classifier, measures model performance with accuracy score.
- **LIME explanation**: Generates local explanations for individual predictions.
- **Anchor explanation**: Produces rule-based explanations for individual predictions. 

## Example Output

- Visual explanation of predictions
- Rule-based explanation for model decisions

## Results

- Achieved competitive performance with Random Forest.
- LIME and Anchor explanations helped build transparency in model predictions.

## Future Improvements

- Try other models (Logistic Regression).
- Enhance preprocessing pipelines.
- Try other XAI methods (SHAP).

## License

This project is open-source, intended as a final project for the course Explainable AI.