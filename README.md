# The Winning Formula: Modeling Athlete and Country Success at the Olympics

## 📌 Project Overview

This project explores the factors influencing Olympic success for both individual athletes and countries. Using machine learning models, we aim to:

- **Predict athlete medal outcomes** based on historical performance and demographic data.
- **Forecast country rankings** in the Olympic Games using past medal records and team composition.

This study leverages *Linear Discriminant Analysis (LDA)*, *Multinomial Logistic Regression*, and *Random Forest Classifiers* to uncover key insights.

This project was conducted in **R** as part of the **independent coursework for McGill MMA MGSC 661**.

---

## 📂 Data Description

The dataset contains Olympic athlete participation records from **1896 to 2016**, with features categorized as follows:

### **Athlete-Level Features**
- **Demographics**: Name, Sex, Age, Height, Weight
- **Participation**: National Olympic Committee (NOC), Event participation, Medal won (Gold, Silver, Bronze, None)
- **Engineered Features**: Home advantage, prior performance, cumulative medals

### **Country-Level Features**
- **Team Composition**: Average age, height, weight of athletes
- **Participation Metrics**: Total events & sports participated
- **Historical Performance**: Previous medal counts (last Olympics & rolling 5-game average)
- **Home Advantage Indicator**: Binary flag for host country

---

## 📊 Models & Methodology

### **1️⃣ Athlete Medal Prediction**
- *Linear Discriminant Analysis (LDA)* for classification
- *Multinomial Logistic Regression* for predicting medal type
- *Feature importance analysis* to interpret key predictors

### **2️⃣ Country Ranking Prediction**
- *Random Forest Classifier* to categorize countries into ranking bins (e.g., Top 5, Top 10)
- *Feature importance analysis* to identify key factors influencing rankings

---

## 🎯 Key Findings

- 🏅 **Home advantage significantly increases the likelihood of winning Gold and Silver medals.**
- 🌍 **Countries with broader participation across sports & events rank higher.**
- 📈 **Past performance (prior medals) is the strongest predictor of future success.**
- 🏠 **Hosting the Olympics correlates with a nation's chances of finishing in the Top 15.**

---

## 📖 Interpretation

- **Experience does not always guarantee success**. While previous medalists have a higher likelihood of winning again, the effect diminishes for athletes with too many prior Olympic appearances, possibly due to aging or competition changes.
- **Historical performance is the best predictor of future rankings**. Countries with consistent success in past Olympic Games continue to dominate, showing the importance of long-term sports investment.

---

## 📩 Contact

**📝 Author:** Katherine Gong  
**📧 Email:** shaojun.gong@mail.mcgill.ca  
**🔗 LinkedIn:** https://www.linkedin.com/in/katherine-shaojun-gong-525262213/

**📌 Course:** MGSC 661 - McGill MMA  
**📅 Date:** December 2024  

Feel free to reach out for collaboration or questions!
