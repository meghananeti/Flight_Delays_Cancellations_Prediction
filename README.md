Flight Delay and Cancellation Prediction System

Team Members:
Sri Sai Srikar Bollapragada
Meghana Neti

Project Overview:
Flight delays and cancellations are significant issues that affect both airlines and passengers, causing inconvenience, financial losses, and operational inefficiencies. This project addresses the problem by developing a machine learning-based system to predict flight delays and cancellations using historical data and various contributing factors like weather conditions, airline performance, and airport congestion.

The system aims to:
Provide real-time predictions of flight delays and cancellations.
Assist airlines in operational planning and resource management.
Help passengers make informed travel decisions.
Business Problem:
Flight delays and cancellations not only disrupt schedules but also impact the overall operational efficiency of airlines. For passengers, delays and cancellations can lead to missed connections, additional costs, and inconvenience. By accurately predicting these disruptions, the system helps airlines proactively manage their operations, minimizing the negative impacts.

Key business benefits include:
Improved customer satisfaction by providing timely alerts.
Optimized resource allocation for airlines.
Enhanced decision-making capabilities regarding flight scheduling and rebooking.
Dataset:

The project uses a comprehensive dataset that combines historical flight data with additional parameters such as:
Weather conditions
Airline performance
Airport congestion
Data Source: Dataverse Harvard Flight Delay Dataset

Methodology:
The project follows the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology:

Business Understanding – Define the problem and objectives.
Data Understanding – Explore the dataset to extract key insights.
Data Preparation – Clean and preprocess the data.
Modeling – Apply various machine learning models.
Evaluation – Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
Deployment – Deploy the best-performing models for real-time prediction.

Machine Learning Models:
The project implements a variety of machine learning algorithms to identify the best model for predicting flight delays and cancellations. These models include:
Decision Trees
Random Forest
Boosting Algorithms (XGBoost)

Key Aspects:
Feature Engineering: Creating new features from raw data to improve model performance.
Handling Class Imbalance: Since flight delays and cancellations are rare events, techniques like class balancing were employed.

Best Models:
XGBoost Regressor: Performed best for delay prediction.
Ensemble Modeling: Outperformed other classifiers for cancellation predictions in an imbalanced class scenario.

Results:
Regression Results: The XGBoost Regressor provided the most accurate predictions for flight delays.
Classification Results: Ensemble modeling delivered the best performance for predicting flight cancellations.

Key Performance Metrics:
Accuracy
Precision
Recall
F1-Score

Conclusion:
The project successfully built a predictive system for flight delays and cancellations using machine learning techniques. The system can be integrated into airline operations to improve efficiency, resource allocation, and customer experience. The project demonstrates that leveraging historical data with advanced algorithms like XGBoost can significantly enhance the ability to predict flight disruptions.

Future Work:
Improve the system by integrating real-time data such as live weather updates.
Develop a user-facing application for passengers to check real-time predictions of flight disruptions.
