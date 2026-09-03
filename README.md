# Subject-Wise Academic Performance Analysis

## 📌 Project Overview

The **Subject-Wise Academic Performance Analysis** project is a Tableau-based data analytics project that analyzes student academic performance across different subjects, grades, classes, attendance ranges, and student groups.

The project helps identify overall performance patterns and understand how academic results vary across different dimensions.

---

## 🎯 Business Problem

Educational institutions need to understand student performance across subjects and identify areas where students or classes may require additional academic support.

This project analyzes student records to answer questions such as:

* What is the overall academic performance of students?
* Which subject has the highest average marks?
* How does performance vary across different classes?
* Is there a noticeable difference in performance across attendance ranges?
* How do subject-wise marks vary across different grades?

---

## 🎯 Objectives

* Analyze overall student academic performance.
* Compare average marks across different subjects.
* Analyze academic performance by class.
* Examine academic performance across attendance ranges.
* Compare subject-wise performance across different grades.
* Build an interactive and easy-to-understand Tableau dashboard.
* Generate meaningful insights from the student dataset.

---

## 📊 Dataset

**Dataset:** Student Records
**Source:** Kaggle

The dataset contains **10,000 student records**.

### Dataset Columns

| Column          | Description                      |
| --------------- | -------------------------------- |
| StudentID       | Unique student identifier        |
| Name            | Student name                     |
| Age             | Student age                      |
| Gender          | Student gender                   |
| Class           | Student class                    |
| Math            | Mathematics marks                |
| Science         | Science marks                    |
| English         | English marks                    |
| History         | History marks                    |
| Computer        | Computer marks                   |
| Attendance      | Student attendance percentage    |
| Extracurricular | Extracurricular activity         |
| Total           | Total marks across five subjects |
| Grade           | Student grade                    |

### Subjects Analyzed

* Mathematics
* Science
* English
* History
* Computer

---

## 🛠️ Tools & Technologies

* **Tableau Desktop**
* **Kaggle Dataset**
* Data Visualization
* Exploratory Data Analysis
* Calculated Fields
* Aggregation and Filtering
* Dashboard Design

---

## 🔄 Project Workflow

### Step 1 — Data Collection & Understanding

The Student Records dataset was collected from Kaggle.

The dataset structure, columns, data types, and available academic attributes were reviewed to determine its suitability for the analysis.

### Step 2 — Data Cleaning & Preparation

The dataset was checked for:

* Missing values
* Blank values
* Categorical values
* Numerical value ranges
* Duplicate Student IDs
* Total marks calculation

No missing or blank values were found, and the categorical and numerical values were verified.

The `Total` column was also verified against the sum of the five subject marks.

### Step 3 — Exploratory Data Analysis

The following analyses were performed using separate Tableau worksheets:

1. Overall Academic Performance
2. Subject-Wise Performance
3. Class-Wise Performance
4. Gender-Wise Performance
5. Grade-Wise Performance
6. Attendance Range vs Academic Performance
7. Extracurricular vs Academic Performance
8. Student Performance by Subject and Grade
9. Class-Wise Subject Performance

### Step 4 — Visualization & Analysis

Five key visualizations were selected for the final dashboard:

1. **Overall Academic Performance**
2. **Subject-Wise Performance**
3. **Class-Wise Performance**
4. **Attendance Range vs Academic Performance**
5. **Student Performance by Subject and Grade**

Each visualization was maintained as a separate Tableau worksheet.

### Step 5 — Dashboard Creation

A final Tableau dashboard was created by combining the five selected worksheets.

The dashboard was organized using horizontal and vertical containers to provide a clean and structured presentation.

### Step 6 — Final Conclusion & Documentation

The final insights were reviewed and documented for portfolio presentation.

---

## 📈 Key Findings

### Overall Performance

* Number of students: **10,000**
* Average total marks: **321.9**
* Minimum total marks: **177**
* Maximum total marks: **475**

### Subject-Wise Performance

| Subject  | Average Marks |
| -------- | ------------: |
| Science  |         64.57 |
| English  |         64.53 |
| Computer |         64.44 |
| History  |         64.33 |
| Math     |         64.04 |

**Science** has the highest average marks, while **Math** has the lowest. However, the difference between subjects is small.

### Class-Wise Performance

* **Class 6** has the highest average total marks: **323.747**
* **Class 8** has the lowest average total marks: **320.495**

Overall, performance across Classes 5–12 is relatively consistent.

### Attendance vs Academic Performance

| Attendance Range | Average Total Marks |
| ---------------- | ------------------: |
| 60–69%           |             321.989 |
| 70–79%           |             321.388 |
| 80–89%           |             322.569 |
| 90–100%          |             321.674 |

The differences between attendance ranges are very small. Therefore, this dataset does **not show a strong relationship between attendance range and average academic performance**.

### Grade-Wise Performance

| Grade | Average Total Marks |
| ----- | ------------------: |
| A     |               459.1 |
| B     |               415.8 |
| C     |               341.3 |
| D     |               271.9 |
| F     |               192.8 |

Average performance decreases consistently from **Grade A to Grade F**.

### Subject Performance by Grade

The final analysis compares the average marks of **Math, Science, English, History, and Computer** within each grade.

The results show a clear decline in subject averages from **Grade A → B → C → D → F**, indicating that grade groups strongly reflect overall academic performance.

---

## 💡 Business Insights

1. **Overall student performance is moderate**, with an average total score of 321.9.
2. **Science performs slightly better** than the other subjects based on average marks.
3. **Class-wise performance is relatively stable**, with only small differences between classes.
4. **Attendance ranges show very similar average marks**, so attendance alone does not appear to explain academic performance in this dataset.
5. **Grade is the strongest visible differentiator** in academic performance.
6. The five subjects generally show a similar performance pattern across the different grades.

---

## 📊 Dashboard

The final Tableau dashboard contains five key visualizations:

* Overall Academic Performance
* Subject-Wise Performance
* Class-Wise Performance
* Attendance Range vs Academic Performance
* Student Performance by Subject and Grade

The dashboard provides a consolidated view of academic performance and allows the major findings to be understood quickly.

---

## 🏁 Final Conclusion

The analysis shows that student academic performance is relatively consistent across classes and attendance ranges, while grade groups provide the clearest distinction in performance.

Subject-wise differences are relatively small, with Science achieving the highest average marks and Math the lowest. The strong decline in average subject marks from Grade A to Grade F indicates that grade classification closely reflects overall academic achievement.

Overall, the Tableau dashboard provides an effective visual summary of student academic performance and can help educational institutions identify performance patterns and areas requiring further investigation.

---

## 📁 Project Structure

```text
Subject-Wise-Academic-Performance-Analysis/
│
├── data/
│   └── Student Records.csv
│
├── tableau/
│   └── Subject-Wise Academic Performance Analysis.twbx
│
├── screenshots/
│   └── dashboard screenshots
│
├── README.md
└── requirements.txt
```

---

## 👤 Author

**Yash Srivastava**

### Project #9 — Data Analytics Portfolio

**Technology:** Tableau
**Domain:** Education / Academic Analytics
