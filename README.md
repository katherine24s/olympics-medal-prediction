# The Winning Formula: Modeling Athlete and Country Success at the Olympics

## 📌 Project Overview

This project explores the factors influencing Olympic success for both individual athletes and countries. Using machine learning models, we aim to:

- Predict athlete medal outcomes based on historical performance and demographic data.

- Forecast country rankings in the Olympic Games using past medal records and team composition.

This study leverages *Linear Discriminant Analysis (LDA)*, *Multinomial Logistic Regression*, and *Random Forest Classifiers* to uncover key insights.

🔍 Data Description

The dataset contains Olympic athlete participation records from 1896 to 2016 with features such as:

Athlete-Level Features

Name, Sex, Age, Height, Weight

National Olympic Committee (NOC)

Event participation & medal won (Gold, Silver, Bronze, None)

Engineered features: home advantage, prior performance, cumulative medals

Country-Level Features

Average age, height, weight of athletes

Total events & sports participated

Previous medal counts (last Olympics & rolling 5-game average)

Binary indicator for home advantage

📊 Models & Methodology

1️⃣ Athlete Medal Prediction

Linear Discriminant Analysis (LDA) for classification

Multinomial Logistic Regression for predicting medal type

Feature importance analysis to interpret significant predictors

2️⃣ Country Ranking Prediction

Random Forest Classifier to categorize countries into ranking bins (e.g., Top 5, Top 10)

Feature importance analysis to identify key factors affecting rankings

🎯 Key Findings

✅ Home advantage significantly boosts the likelihood of winning Silver and Gold medals
✅ Countries with broader participation across sports & events rank higher
✅ Past performance (prior medals) is the strongest predictor of future success
✅ Hosting the Olympics increases a nation's chance of finishing in the Top 15

🚀 How to Reproduce the Analysis

1️⃣ Upload Your Files to GitHub

Instead of cloning, manually upload the necessary files:

Upload datasets to the data/ folder.

Upload project_report.Rmd to the notebooks/ folder.

Upload your final report (Final_Gong.pdf) to the reports/ folder.

Upload modeling scripts to the src/ folder.

2️⃣ Install Dependencies

Ensure you have R and the necessary packages installed:

install.packages(c("tidyverse", "caret", "nnet", "randomForest", "MASS"))

3️⃣ Run the Analysis

Open notebooks/olympic_analysis.Rmd and knit the report.

Run src/medal_prediction.R for athlete medal classification.

Run src/country_ranking.R for predicting country rankings.

📩 Contact

📝 Author: Katherine Gong📧 Email: shaojun.gong@mail.mcgill.ca🔗 LinkedIn: linkedin.com/in/katherinegong

📌 Course: MGSC 661 - McGill MMA📅 Date: February 2025

Feel free to reach out for collaboration or questions!
