# Data Science Internship – Bank Marketing Analysis

**Virtual Data Science with Python Apprentice Internship | YuvaIntern**

## About the Project

This project was completed as part of my five-week Data Science internship with YuvaIntern. I worked with the Bank Marketing dataset to understand customer behavior and identify patterns in term deposit subscriptions.

Throughout the project, I used Python to explore data, create visualizations, perform statistical analysis, and build machine learning models. The goal was to understand customer subscription patterns and explore how data-driven insights can support better marketing decisions.

## Objectives

* Analyze customer data and identify important patterns.
* Create visualizations to understand subscription behavior.
* Perform statistical hypothesis testing.
* Build and evaluate machine learning models.
* Identify useful insights and suggest improvements to customer targeting.

## Dataset

The Bank Marketing dataset contains **45,211 records and 17 columns**.

* **Target variable:** `y`
* **Target values:** `yes` and `no`
* **Problem type:** Binary classification
* **Dataset path:** `data/bank-full.csv`

Approximately 11.70% of customers subscribed to a term deposit, making class imbalance an important consideration during model evaluation.

## Tools and Technologies

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* Jupyter Notebook
* Git and GitHub

## Project Workflow

The project was completed in five stages:

* **Week 1 – Exploratory Data Analysis:** Explored the dataset, checked data quality, and examined customer characteristics.
* **Week 2 – Data Visualization:** Created visualizations to understand customer patterns and subscription behavior.
* **Week 3 – Hypothesis Testing:** Used statistical tests to investigate relationships between customer characteristics and subscriptions.
* **Week 4 – Machine Learning:** Built and compared Logistic Regression and Decision Tree models.
* **Week 5 – Final Analysis:** Summarized the findings, reviewed subscription rates, and prepared the final project report.

## Model Results

| Metric               | Logistic Regression | Decision Tree |
| -------------------- | ------------------: | ------------: |
| Accuracy             |              84.57% |        83.00% |
| Subscriber Precision |               41.8% |         39.3% |
| Subscriber Recall    |               81.5% |         83.4% |
| Subscriber F1-score  |               55.3% |         53.5% |

Logistic Regression achieved higher accuracy and F1-score, while the Decision Tree achieved slightly higher recall for subscribers.

## Key Learnings

This project gave me practical experience in data analysis, visualization, statistical testing, and machine learning. It also helped me understand model evaluation, class imbalance, and how analytical findings can be translated into useful business insights.

## Repository Structure

```text
YuvaIntern_Data_Science_Internship/
├── data/
├── Week_1/
├── Week_2/
├── Week_3/
├── Week_4/
├── Week_5/
├── README.md
└── requirements.txt
```

Each weekly folder contains the corresponding project work, such as notebooks, charts, and reports.

## How to Run

Clone the repository:

```bash
git clone https://github.com/Muneeb2739/YuvaIntern_Data_Science_Internship.git
```

Navigate to the project folder:

```bash
cd YuvaIntern_Data_Science_Internship
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook you want to explore. Make sure the dataset is available in the expected `data/` folder.

## Conclusion

This internship project helped me apply data science techniques to a real-world marketing problem. By working through data exploration, statistical analysis, and machine learning, I gained a better understanding of how Python can be used to identify patterns, evaluate predictions, and support data-driven decisions.

## Author

**Mohammed Muneeb**

GitHub: [Muneeb2739](https://github.com/Muneeb2739)

**Project Repository:** [YuvaIntern Data Science Internship](https://github.com/Muneeb2739/YuvaIntern_Data_Science_Internship)
