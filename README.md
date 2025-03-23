🚢 Titanic Survival Predictions
Predicting the survival of Titanic passengers using machine learning.

📌 Overview
This project uses machine learning to predict whether a passenger survived the Titanic disaster. The dataset contains details like age, gender, ticket class, and fare, which are used to build and evaluate different models.

📊 Dataset Details
train.csv → Used for training the model

test.csv → Used for testing the model

✅ Key features:

Pclass: Ticket class (1st, 2nd, 3rd)

Sex: Passenger gender

Age: Passenger age

Fare: Ticket price

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived: Survival status (0 = No, 1 = Yes)

🔥 Technologies Used
Python (pandas, numpy) → Data cleaning & preprocessing

Matplotlib & Seaborn → Data visualization

Scikit-Learn → Model building & evaluation

🚀 Approach
Data Cleaning & Preprocessing

Handled missing values (Age, Embarked)

Encoded categorical variables

Scaled numerical features

Exploratory Data Analysis (EDA)

Visualized survival rates by gender, class, and age

Heatmaps to identify correlations

Model Building

Trained multiple models:

Logistic Regression

Random Forest

Decision Tree

Compared accuracy, precision, and recall

📈 Results
Model Accuracy:

Logistic Regression → 81.2%

Random Forest → 85.4%

Decision Tree → 79.6%

✅ Key insights:

Women and children had a higher survival rate.

First-class passengers were more likely to survive.

Fare price and age influenced survival chances.

🔧 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Yechinalokesh/PRODIGY_DS_TASK2.git
Install the required libraries:

nginx
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Open and run the notebook:

nginx
Copy
Edit
jupyter notebook Titanic_Survival_Predictions.ipynb
🚀 Next Steps
Try more advanced models like XGBoost and LightGBM

Perform hyperparameter tuning for better accuracy

Experiment with feature selection techniques

👤 Author
Yechina Lokesh

GitHub: Yechinalokesh

LinkedIn: Lokesh Yechina

Email: lokeshyechina@gmail.com
