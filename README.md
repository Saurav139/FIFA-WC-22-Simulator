# ⚽ FIFA World Cup 2022 Simulator

A machine learning-based simulator designed to predict the outcomes of the FIFA World Cup 2022, using a classification model trained on historical data, current world rankings, and a custom form index. This project explores different prediction algorithms and evaluates their effectiveness in simulating the entire tournament.

## 🔍 Overview
- **Dataset**: The model uses a combination of historical match results, FIFA World Cup rankings, and qualification match statistics. Data was collected from sources like Kaggle and web scraping using BeautifulSoup.
- **Features**: Historical win percentage, FIFA rankings, and a custom feature called "form index" based on recent team performance.

## 📊 Methodology
- **Algorithms Used**: Logistic Regression, Decision Tree, and Random Forest were evaluated.
- **Training Data**: The model was trained using the 2018 World Cup data and evaluated on the ongoing 2022 World Cup data.
- **Hyperparameter Tuning**: Multiple solvers like Limited-Memory BFGS and liblinear were explored for Logistic Regression.

## 🚀 Results
- **Model Accuracy**:
  - Logistic Regression: 58.3%
  - Decision Tree: 99% (suffered from overfitting)
  - Random Forest: 100% (better feature balance but diminished form index importance)
- **Prediction Performance**: The Logistic Regression model predicted 75% of the Round of 16 teams correctly for the 2018 World Cup and had at least 50% accuracy for other knockout stages.

## 🏆 Conclusion
While more sophisticated models like Decision Tree and Random Forest showed higher training accuracy, the Logistic Regression model provided more realistic predictions, making it the most suitable for simulating a knockout tournament.

## 📚 References
- [Kaggle Dataset: International Football Results](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)
- FIFA World Rankings scraped with BeautifulSoup

---

This project was developed by Saurav Krishna & Sadasivam Natanakumar for exploring the applications of machine learning in sports analytics.
