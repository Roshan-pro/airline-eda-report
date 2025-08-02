# ✈️ Airline Availability Prediction using EDA + ML

This project focuses on analyzing a dataset of flight bookings and building a machine learning model to **predict the Airline** based on flight details. Alongside, it includes a beautifully styled **interactive HTML EDA report** generated using `ydata-profiling`.

📍 **Live Report**:  
[🌐 View HTML EDA Report](https://roshan-pro.github.io/airline-eda-report/)  
📌 *(Works on mobile and desktop — interactive elements included!)*

---

## 📂 Dataset Overview

The dataset contains the following key features:

| Feature            | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `Airline`          | 🏷️ Target variable – Airline name (6 categories)                            |
| `Flight`           | Unique flight code                                                          |
| `Source City`      | City of departure                                                           |
| `Departure Time`   | Categorical bin of time of day                                              |
| `Stops`            | Number of stops between cities (0, 1, or 2+)                                |
| `Arrival Time`     | Arrival time bin                                                           |
| `Destination City` | Destination city                                                            |
| `Class`            | Seat class (Business or Economy)                                            |
| `Duration`         | Total travel time (in hours)                                                |
| `Days Left`        | Days left until travel date                                                 |

---

## 🔍 Project Highlights

- ✅ Exploratory Data Analysis (EDA)
- ✅ Outlier handling (Winsorization)
- ✅ Distribution & categorical analysis
- ✅ Cardinality and rare category detection
- ✅ Chi-Square Association and Correlation
- ✅ Feature leakage detection
- ✅ Airline prediction using Decision Tree Classifier
- ✅ 📄 Auto-generated interactive HTML report

---

## 🛠️ Tools & Libraries

- Python
- pandas, matplotlib, seaborn
- ydata-profiling
- scikit-learn
- numpy

---

## 🧠 Model Used

A **Decision Tree Classifier** was trained to predict the **Airline** using features like source, destination, time, class, duration, etc. Cross-validation and performance metrics were used for evaluation.

---

## 📊 Report

You can view the auto-generated EDA report here:  
👉 [https://roshan-pro.github.io/airline-eda-report/](https://roshan-pro.github.io/airline-eda-report/)

The report includes:
- Overview stats
- Missing value visualization
- Univariate & bivariate plots
- Correlation matrix
- Interactivity (expand/collapse tables, charts)


## 🙌 Support

If you found this project helpful:
- ⭐ Star the repo
- ✅ Upvote my [Kaggle Notebook](https://www.kaggle.com/code/roshan123kumar/airlines-flight-analysis-prediction)
- 🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/roshan-kumar-670529317/)

---

## 📬 Contact

**Roshan Kumar**  
📧 rk1861303@gmail.com  
🎓 B.Sc. Computer Science and Data Analytics @ IIT Patna  
🚀 Aspiring AI/ML Researcher

---



