# Fantasy Football Running Back Performance Analysis & Forecasting

**This project explores fantasy football performance data to identify the most productive NFL running backs and forecast future outcomes based on key statistical indicators. Using Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn), I conducted a full end-to-end data analysis pipeline — from data preparation and visualization through model development and evaluation.**

#### Workflow Overview:

Data Collection & Cleaning – Imported multi-season fantasy football data, standardized player stats, filtered for running backs, and handled missing or inconsistent records.

Exploratory Data Analysis (EDA) – Visualized distributions of fantasy points, rushing yards, touchdowns, and receptions to uncover trends and outliers among top RBs.

Feature Engineering – Created derived metrics such as yards per carry and fantasy points per game to enhance predictive features.

Model Development – Implemented a Linear Regression model to predict fantasy points from performance metrics (rushing yards, touchdowns, fumbles, receptions, etc.).

Evaluation & Interpretation – Measured model accuracy using R² and Mean Squared Error (MSE). Interpreted coefficient weights to determine which factors had the greatest influence on fantasy value.

Forecasting Insights Applied the trained model to project next-season fantasy performance, highlighting potential breakout or undervalued running backs.

#### Key Findings:

Touchdowns and rushing yards had the strongest correlation with total fantasy output.

Players with high yards per carry but low volume represented strong upside candidates for future seasons.

Regression performance showed strong predictive alignment, validating the feature selection and model approach.

#### Tech Stack:
Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
