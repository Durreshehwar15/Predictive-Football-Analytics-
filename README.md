# Predictive-Football-Analytics-
Developed a data-driven football analytics project using the Metrica Sports dataset to analyze player movements and shot events. The project involved preprocessing and merging large-scale tracking and event data, including player positions, passes, interceptions, goals etc
This project uses integrated event and tracking data from the open-source Metrica Sports
dataset to analyze the dynamics of football matches. We investigate two important areas:
modeling team possession and predicting shot success. XGBoost and Random Forest
performed the best when we used classification models (logistic regression, random forest,
SVM, KNN, and XGBoost) to predict shot outcomes following a great deal of preprocessing
and feature engineering (e.g., shot distance, angle, and player positions). Using only tracking
data, possession was modeled as a regression task. Our aim is to provide a simple procedure
that can be used for practical soccer data analysis tasks and also serve as a baseline model for
algorithms based on more advanced approaches. The resulting algorithm is fast, easy to
implement, achieves high accuracy on the datasets available to us, and can be used in similar
scenarios without modification.
