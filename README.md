# Support-Vector-Regression-SVR-Tips-Dataset-Analysis

This project demonstrates how Support Vector Regression (SVR) can be applied to a real-world dataset containing restaurant billing information. The objective is to predict tip amount based on various numerical and categorical features.

The project includes data preprocessing, feature selection, encoding, SVR model training, and performance evaluation using regression metrics.
📌 Dataset Information

The dataset contains the following features:
| Feature        | Description                    |
| -------------- | ------------------------------ |
| **total_bill** | Total bill amount (in dollars) |
| **tip**        | Tip amount                     |
| **sex**        | Gender of the person paying    |
| **smoker**     | Whether the person is a smoker |
| **day**        | Day of the week                |
| **time**       | Lunch or Dinner                |
| **size**       | Number of people at the table  |

🧪 Project Workflow
✔️ 1. Data Cleaning & Preprocessing

Handled categorical columns using LabelEncoder

Converted dataset into a numerical format suitable for SVR

Used numpy.set_printoptions to control display formatting

✔️ 2. Feature Selection

Selected meaningful features using:

Correlation matrix

Manual domain understanding

Dropping irrelevant fields if needed

✔️ 3. Model Training (Support Vector Regression – SVR)

Trained SVR with:

Kernel = "rbf" (or polynomial/linear based on tuning)

Scaled numeric features for model stability

✔️ 4. Train-Test Split

Using from sklearn.model_selection

📈 Evaluation Metrics

The model is evaluated using:

🔹 R² Score

Measures how well the regression predictions approximate the real data.

🔹 Mean Absolute Error (MAE)

Represents how far predictions are from actual tips on average.

📊 Visualizations


Scatter plots (total_bill vs tip)

SVR prediction curves

Residual plots

🧠 Technologies & Libraries Used

Python

NumPy

set_printoptions

Pandas

Scikit-learn

SVR

LabelEncoder

train_test_split

r2_score

mean_absolute_error

Matplotlib / Seaborn (for plots)
