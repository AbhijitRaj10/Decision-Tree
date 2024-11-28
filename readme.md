# Stroke Prediction Using Decision Tree

## Overview

This project uses a Decision Tree model to predict the likelihood of a stroke based on various health indicators. The goal is to assist in early detection and preventive measures.

## Dataset

The dataset includes features like:
- `age`: Age of the patient.
- `hypertension`: Hypertension status (1: Yes, 0: No).
- `heart_disease`: Heart disease presence (1: Yes, 0: No).
- `avg_glucose_level`: Average glucose level in the blood.
- `bmi`: Body Mass Index.
- `stroke`: Target variable (1: Stroke occurred, 0: No stroke).

## How to Run


1. **Open Notebook**: Launch Jupyter Notebook and open `DECISIONtree.ipynb`:
    ```bash
    jupyter notebook DECISIONtree.ipynb
    ```

2. **Execute the Code**: Run each cell sequentially to load the data, preprocess it, train the Decision Tree model, and evaluate its performance.

## Results

The Decision Tree model achieved satisfactory accuracy, and feature importance analysis identified critical predictors of strokes. Improvements can be made by incorporating advanced techniques like cross-validation and hyperparameter tuning.

## Future Improvements

- **Feature Engineering**: Create new features to better capture relationships in the data.
- **Handle Class Imbalance**: Address imbalance in target classes to improve minority class predictions.
- **Model Comparisons**: Explore advanced models like Random Forests or Gradient Boosting.
- **Visualizations**: Enhance interpretability with more insightful visualizations.

## Conclusion

This project showcases the application of Decision Tree models in healthcare analytics, offering a foundation for building robust stroke prediction systems.

---

### License

This project is licensed under the MIT License.
