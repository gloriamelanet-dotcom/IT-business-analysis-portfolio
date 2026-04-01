# IT-business-analysis-portfolio
Portfolio to show data/business analysis skills

analysis (1).md

# 📊 Sales Performance Analysis

## 🎯 Objective
The goal of this project is to analyze sales data to identify trends, top-performing products, and provide business insights that can help increase revenue.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset
The dataset contains:
- Monthly sales data
- Top-performing product for each month

---

## 🔍 Analysis Performed
- Loaded and explored the dataset
- Checked for missing values
- Analyzed monthly revenue trends
- Identified top-performing products
- Created visualizations using Matplotlib

---

## 📈 Key Insights
- Sales increase steadily toward the end of the year
- December has the highest revenue (seasonal demand)
- Product A is the most frequently top-performing product
- Mid-year sales are relatively stable

---

## 📊 Visualizations

### 📉 Monthly Sales Trend
![Sales Trend](images/sales_trend.png)

### 📊 Top Performing Products
![Top Products](images/top_products.png)

---

## 💡 Business Recommendations
- Increase marketing efforts in Q4 (October–December)
- Stock more of high-performing products like Product A
- Investigate ways to boost mid-year sales performance


## 📊 Analysis Summary

- December has the highest sales → seasonal demand
- Early months show lower performance
- Product A dominates most months
- Sales trend increases toward year-end

## 💡 Business Insight

The company should:
- Increase marketing in Q4
- Focus on high-performing products

---

## 🚀 Conclusion
This project demonstrates how data analysis can be used to uncover business insights and support better decision-making.

student-analysis.ipynb

# 🎓 Student Performance Analysis

## 📌 Objective

The goal of this project is to analyze student academic performance using data analysis techniques to identify trends, strengths, and areas that require improvement.

## 🛠 Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## 📂 Dataset

* Student performance dataset (CSV file) containing marks for:

  * Math
  * English
  * Science

## 🔍 Process

* Loaded the dataset using Pandas
* Checked for missing values and understood data structure
* Calculated average marks per subject
* Created a total score for each student
* Identified top-performing students
* Visualized data using bar charts and histograms

## 📈 Key Insights

* Math has the lowest average score, indicating a need for academic intervention
* Science is the highest-performing subject overall
* Top-performing students consistently score above 85 across all subjects
* Most students fall within the 70–90 mark range

## 📊 Visualizations

* Bar chart showing average marks per subject
* Histogram showing distribution of Math scores

![Average Marks](images/average_marks.png)
![Math Distribution](images/math_distribution.png)

## 🚀 Conclusion

This analysis highlights key academic trends and provides insights that can help educators improve student performance by focusing on weaker subjects and supporting struggling students.

customer-analysis

# 📉 Customer Satisfaction Analysis

## 📌 Objective

The goal of this project is to analyze customer satisfaction data to identify key factors affecting customer experience and provide actionable business recommendations.

## 🛠 Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## 📂 Dataset

* Customer dataset containing:

  * Customer ratings
  * Response time
  * Number of complaints
  * Resolution status

## 🔍 Process

* Loaded and explored the dataset using Pandas
* Analyzed overall customer satisfaction (average rating)
* Investigated the relationship between response time and ratings
* Examined how complaints impact customer satisfaction
* Evaluated the effect of issue resolution on customer ratings
* Created visualizations to support findings

## 📈 Key Insights

* Longer response times lead to lower customer ratings
* Customers with more complaints tend to give lower ratings
* Unresolved issues significantly reduce customer satisfaction
* Faster response times (1–3 hours) are associated with higher ratings

## 💼 Business Recommendations

* Improve customer support response time
* Ensure all customer issues are resolved promptly
* Implement tracking systems for unresolved complaints
* Train support teams to handle issues more efficiently

## ⚠️ Technical Note

During the project, an error occurred when saving visualizations:

```
No such file or directory: 'images/resolution_impact.png'
```

### 🔍 Reason:

This happened because the `images` folder did not exist or the file path was incorrect at the time of saving.

### ✅ Solution:

* Created the `images` folder manually
* Updated the file path to ensure correct saving location

Despite this, all visualizations were successfully generated and displayed within the notebook.

## 📊 Visualizations

* Response Time vs Rating (scatter plot)
* Complaints vs Rating (scatter plot)
* Resolution Impact on Ratings (bar chart)

## 🚀 Conclusion

This analysis identifies response time and issue resolution as critical drivers of customer satisfaction. Addressing these areas can significantly improve customer experience and retention.

