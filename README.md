# Linear-regression-python-predictive-model-project-
This project applies **Linear Regression** to predict **first-day content viewership** on the ShowTime OTT platform. The goal is to provide actionable insights that help improve content performance and optimize marketing strategies.
Predictive Modeling for ShowTime OTT
📌 Overview
This project uses predictive modeling with linear regression to analyze and forecast first-day content viewership on the ShowTime OTT platform. The goal is to identify the factors that drive audience engagement and provide actionable recommendations for improving content performance.

🛠️ Problem Statement
OTT platforms face challenges in maximizing first-day views due to:

Decline in visitors

Reduced marketing spend

Content timing clashes

Weekend vs weekday releases

Seasonal variations

This project builds a regression model to determine which variables most influence first-day content views.

📂 Dataset
Size: 1,000 records

Features: 8 columns

Key Variables:

Visitors (millions)

Ad impressions (millions)

Major sports event (binary)

Genre (Comedy, Drama, Sci-Fi, etc.)

Day of release

Season of release

Trailer views (millions)

Content views (millions, target variable)

No missing or duplicate values were found. Outliers were retained to study their impact.

🔍 Exploratory Data Analysis (EDA)
Content Views: Average ~0.47M, right-skewed distribution

Genres: Sci-Fi and Action perform best on average

Day of Release: Saturday shows highest average views

Seasonal Trends: Summer releases attract more viewers

Correlation: Trailer views strongly correlate with content views (0.75)

Ad Impressions: Weak correlation with content views

🧑‍💻 Modeling Approach
Method: Linear Regression (OLS)

Feature Engineering: One-hot encoding for categorical variables (genre, day, season)

Performance:

Train R² ≈ 0.77

Test R² ≈ 0.78

Key Predictors: Visitors, trailer views, day of release (Saturday, Wednesday, Sunday), season (Summer, Winter, Spring), and genre (Sci-Fi, Thriller, Comedy, Drama, Horror).

📈 Results
Strong predictive accuracy (R² ≈ 0.78)

Trailer views and visitors are the most significant drivers of first-day content views

Weekend releases outperform weekday releases

Summer releases yield higher engagement

Ad impressions alone do not guarantee higher views

💡 Business Recommendations
Invest in trailer marketing – trailer views strongly predict content success.

Schedule releases on weekends – Saturday yields the highest engagement.

Leverage summer season – plan major releases during holidays.

Focus on Sci-Fi & Action genres – consistently attract higher views.

Grow visitor base – increasing platform visitors directly impacts viewership.

⚙️ Tools Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Statsmodels, Scikit-learn

🔮 Future Enhancements
Integrate live OTT data feeds via API

Deploy interactive dashboards with Streamlit

Experiment with advanced ML models (Random Forest, XGBoost)

Add recommendation system for personalized content suggestions
