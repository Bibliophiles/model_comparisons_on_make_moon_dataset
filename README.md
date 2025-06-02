# 🧠 Model Comparison on make_moons Dataset

This project presents a comparative analysis of four machine learning models on the well-known `make_moons` synthetic dataset. The goal was to evaluate the performance of each model in terms of classification accuracy and loss, highlighting their strengths and limitations on a non-linearly separable dataset.

## 📊 Models Evaluated

- **Artificial Neural Network (ANN)**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **XGBoost Classifier**

## 📈 Results Summary

| Model                     | Accuracy | Loss     |
|--------------------------|----------|----------|
| Artificial Neural Network| **0.985**  | **0.0349** |
| Random Forest Classifier | 0.970    | 0.0726   |
| Support Vector Machine   | 0.875    | 0.2938   |
| XGBoost Classifier       | 0.975    | 0.0679   |

> ✅ The Artificial Neural Network achieved the highest accuracy and lowest loss, making it the best-performing model on this dataset.

## 🛠️ Dataset

- **make_moons** from `sklearn.datasets`
- A toy dataset useful for evaluating classification algorithms on non-linearly separable data.

## 📁 File Structure
- ├── Research.ipynb # Jupyter notebook with model implementation and results
- ├── README.md # Project overview and documentation


## 📦 Dependencies

Install the necessary libraries before running the notebook:

```bash
pip install pandas scikit-learn xgboost
```
## 🚀 How to Run
- Clone the repository and run locally or on Google Colab
```bash
git clone https://github.com/Bibliophiles/model_comparisons_on_make_moon_dataset.git
cd model_comparisons_on_make_moon_dataset
```

## 💡 Future Improvements
Refactor metrics and model outputs into variables for better maintainability.

Experiment with additional models (e.g., k-NN, Logistic Regression).

Add cross-validation and hyperparameter tuning.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

