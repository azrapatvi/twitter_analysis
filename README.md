# **README – Twitter Data Analytics Dashboard**

## **Project Title:**

**Twitter Data Analytics Dashboard using Power BI and Python**

---

## **1. Project Overview**

This project focuses on analyzing a **Twitter dataset** using **Python for data cleaning and preprocessing** and **Power BI** for data visualization and interactive dashboard creation.

The main goal was to extract meaningful insights from the dataset and represent them visually through six detailed dashboards.

### Project Resources

- **Google Colab Notebook:** https://colab.research.google.com/drive/15DXL4iheCExNcxE7MwoJDE4J2SgwkyGp
- **Dashboard:** https://app.powerbi.com/view?r=eyJrIjoiODY0ZWNhZTUtZmEyMi00N2VkLWIyMDktMTBlMGM3MTg4NDZkIiwidCI6IjdiOTUzZWFjLTA3NjEtNGUyZC1iNTRmLWE5MjAwNGZjNTMzYSJ9
- **Project Report:** https://drive.google.com/file/d/1ENeMSV-9yfBoGYcBn8bEf5S0xOjwBbyQ/view?usp=sharing
  

---

## **2. Tools and Technologies Used**

* **Python** (for preprocessing and cleaning data)
* **Power BI** (for data visualization and dashboard creation)
* **Pandas, NumPy, Matplotlib, Seaborn**
* **Microsoft Excel / CSV Dataset**
* **Google, YouTube, and AI tools** (for DAX learning and troubleshooting)

---

## **3. Project Objectives**

* Clean and preprocess the raw Twitter dataset using Python.
* Develop **six interactive Power BI dashboards** to visualize engagement patterns.
* Apply advanced filtering logic to derive meaningful insights.
* Identify trends and behaviors based on tweet type, engagement, and time of posting.
* Strengthen technical and analytical skills through real-time data handling.

---

## **4. Data Preprocessing (Python)**

The dataset was first imported into Python and cleaned for missing values and formatting issues.
A histogram of impressions was also plotted to analyze distribution and identify outliers.
All cleaned data was then used to build Power BI dashboards.

**Google colab Link:** https://colab.research.google.com/drive/15DXL4iheCExNcxE7MwoJDE4J2SgwkyGp

---

## **5. Power BI Dashboard Development**

After cleaning the data, six dashboards were developed in **Power BI**, each representing a distinct analytical task.

---

### **Task 1 – Scatter Chart: Media Engagement vs. Media Views**

**Objective:**
Analyze the relationship between media engagements and media views for tweets with more than 10 replies and engagement rate above 5%.

**Filters Applied:**

* Time: 6 PM–11 PM IST
* Odd tweet dates
* Word count > 50

**Observation:**
No tweets matched all criteria, resulting in an empty graph.

**Insight:**
Strict filters can eliminate all valid data points, emphasizing the need for balanced filtering in analysis.

---

### **Task 2 – Clustered Bar Chart: Engagement Clicks by Tweet Category**

**Objective:**
Compare **URL clicks**, **profile clicks**, and **hashtag clicks** for different tweet categories.

**Filters Applied:**

* Time: 3 PM–5 PM IST
* Even tweet dates
* Word count > 40

**Observation:**

* Link tweets generated the highest URL clicks (2136).
* Profile clicks were also highest for link tweets.
* Hashtag clicks remained low.

**Insight:**
Link-based tweets attract the most engagement, while hashtags have limited effect.

---

### **Task 3 – Top 10 Tweets by Engagement**

**Objective:**
Identify the **top 10 tweets** by combined engagement (likes + retweets).

**Filters Applied:**

* Weekdays only
* Odd tweet dates
* Even impressions
* Word count < 30
* Time: 3 PM–5 PM IST

**Observation:**
Top tweet received **88 total interactions**, outperforming others (19–32 range).
Short tweets performed better.

**Insight:**
Concise tweets generate stronger engagement than lengthy ones.

---

### **Task 4 – Line Chart: Monthly Engagement Trend**

**Objective:**
Compare the **average engagement rate per month** for tweets with and without media.

**Filters Applied:**

* Even engagement
* Odd tweet dates
* Character count > 20
* Excluded words containing “C”
* Time: 3 PM–5 PM & 7 AM–11 AM IST

**Observation:**
Only non-media tweets appeared with very low engagement (0.01 rate).

**Insight:**
Media-based tweets significantly outperform text-only tweets.

---

### **Task 5 – Replies, Retweets, and Likes for High Media Engagement Tweets**

**Objective:**
Compare replies, retweets, and likes for tweets with **media engagement above median**.

**Filters Applied:**

* Time: 7–11 AM & 3–5 PM IST
* June–August 2020
* Odd tweet dates
* Even media views
* Character count > 20
* Excluded words containing “S”

**Observation:**
No data matched all filters.

**Insight:**
Limited dataset size and strict criteria can lead to empty visuals.

---

### **Task 6 – Engagement Rate: With App Opens vs. Without App Opens**

**Objective:**
Compare engagement rates for tweets **with vs. without app opens**.

**Filters Applied:**

* Weekdays: 9 AM–5 PM
* Even impressions
* Odd tweet dates
* Character count > 30
* Excluded words containing “D”
* Time: 12–6 PM & 7–11 AM IST

**Observation:**
No tweets matched all applied filters; metrics were zero.

**Insight:**
Highlights the importance of **data sufficiency and realistic filtering** in dashboard creation.

---

## **6. Conclusion**

This project provided hands-on experience in transforming raw data into structured insights through **Python preprocessing** and **Power BI visualization**.
It strengthened my technical foundation in data analytics and improved my ability to interpret and present real-world insights effectively.

---

## **7. Project Evidence**

Power bi dashbaord link: https://app.powerbi.com/view?r=eyJrIjoiODY0ZWNhZTUtZmEyMi00N2VkLWIyMDktMTBlMGM3MTg4NDZkIiwidCI6IjdiOTUzZWFjLTA3NjEtNGUyZC1iNTRmLWE5MjAwNGZjNTMzYSJ9

colab link: https://colab.research.google.com/drive/15DXL4iheCExNcxE7MwoJDE4J2SgwkyGp 

some Screen shots:
<img width="1159" height="658" alt="image" src="https://github.com/user-attachments/assets/09ad7b0d-6bb4-4a96-bac4-26f3d25a4643" />


---
