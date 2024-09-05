# Customer Purchase Predictor

This project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used contains various features such as age, job, marital status, balance, and previous campaign information. The target variable is `deposit`, which indicates if the customer will make a purchase (Yes/No).

## Project Structure

The project consists of the following steps:

1. **Data Preprocessing**: Handling categorical variables and encoding them to numeric format.
2. **Model Training**: Training a decision tree classifier on the customer data.
3. **Evaluation**: Evaluating the model's performance using a confusion matrix and classification report.
4. **Visualization**: Visualizing the trained decision tree for better interpretability.

## Dependencies

The following Python libraries are required to run the project:

- `pandas`
- `scikit-learn`
- `matplotlib`

You can install these dependencies via pip:

```bash
pip install pandas scikit-learn matplotlib
