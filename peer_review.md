# Peer Review of: [Prince's Notebook](https://github.com/don4ye/ml_regression_prince/blob/main/regression_prince.ipynb)

---

## 🔹 1. Clarity & Organization  
Prince’s notebook is cleanly structured with numbered sections that align with the assignment instructions. The combination of markdown cells and visualizations makes the flow easy to follow. Reflection boxes were placed appropriately after each section.

✅ **Suggestion:** Add a few inline code comments to explain what's happening inside each cell for someone less familiar with Python.

---

## 🔹 2. Feature Selection & Justification  
The features chosen (age, BMI, smoker, etc.) clearly relate to predicting medical insurance charges. Prince gave valid reasoning for each selection, especially highlighting the importance of smoking status.

✅ **Suggestion:** Prince could try interaction terms (e.g., `bmi × smoker`) or explore correlations to deepen justification for or against including features.

---

## 🔹 3. Model Performance & Comparisons  
All three models were implemented: baseline linear regression, pipeline with scaling, and polynomial regression. R², MAE, and RMSE were calculated for each model and discussed in the reflection.

✅ **Suggestion:** A visual summary of the performance metrics (e.g., bar chart comparing RMSE/R² for each model) could make the comparisons easier to interpret.

---

## 🔹 4. Reflection Quality  
Reflections were clearly written, thoughtful, and insightful. Prince did a good job explaining what was learned at each stage and what could be improved or explored with more time.

✅ **Suggestion:** Could briefly mention future steps like regularization (Lasso/Ridge) or using GridSearchCV for hyperparameter tuning.

---

**✅ Overall Score:** 🌟🌟🌟🌟⭐ (4.5/5)  
Well-documented and insightful work. A solid example of applying regression analysis and pipelines effectively in a real-world scenario.

