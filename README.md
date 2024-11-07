# Stroke-Alert-Alerting-Healthcare-Professionals-to-Potential-Stroke-Risk

This project is designed to alert healthcare providers and patients of potential stroke risks by leveraging machine learning models and interactive visualizations.

## Project Overview
- **Objective**: Develop a predictive system for stroke risk to support timely interventions by healthcare professionals.
- **Tech Stack**: Python, Streamlit, scikit-learn, NLP techniques, and machine learning algorithms (Random Forest, SVM).
- **Model Performance**: Achieved an 87% accuracy rate after hyperparameter tuning and cross-validation.

## Files and Structure
1. **Data Files**:
   - `healthcare-dataset-stroke-data.csv`: Original dataset containing stroke-related data.
   - `stroke_prediction_cleaned.csv`: Cleaned dataset with preprocessed data.
   - `resampled_df_stroke.csv`: Resampled dataset to address any data imbalances.
   
2. **Notebooks**:
   - `data_preprocessing.ipynb`: Notebook containing data cleaning and preprocessing steps.
   - `modelling.ipynb`: Notebook for model training and evaluation, exploring Random Forest, SVM, and NLP models with detailed performance metrics.

3. **Model and App Files**:
   - `rf_model.pkl`: Saved Random Forest model for stroke prediction.
   - `app.py`: Streamlit app that provides an interactive user interface for healthcare professionals and patients to assess stroke risk.

4. **Dependencies**:
   - `requirements.txt`: List of required libraries and dependencies.

## How to Run the Project
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Streamlit app by executing `streamlit run app.py` in the terminal.
4. The app will open in your default browser, where you can interact with the interface to assess stroke risk.