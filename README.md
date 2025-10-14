# titanic-task
# Titanic Survival Prediction

This project predicts the probability of survival for Titanic passengers using a Random Forest model.

## How to run

1. Install dependencies:
pip install -r requirements.txt
2. Open `notebook.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells to preprocess data, train the model, and test predictions.

## Example

You can use the `predict_survival` function:

```python
prob = predict_survival(
 pclass=3, age=40, sibsp=1, parch=0, fare=7.25,
 sex_male=0, embarked_Q=0, embarked_S=1, deck_Unknown=1
)
print(f"Survival probability: {prob:.2f}")
