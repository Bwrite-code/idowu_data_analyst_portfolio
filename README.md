# Greenfield Academy Student Performance Analytics

## Project Overview

**Project Type:** Education Data Analytics  
**Focus:** Student Performance and Attendance  
**Dataset:** Student Report Card Dataset  
**Primary Analysis:** Academic performance, attendance and automated reporting

---

## Business Problem

Greenfield Academy's manual student reporting process creates opportunities for data-entry errors, inconsistent calculations and inefficient report generation.

This project focused on developing a dynamic report card model that retrieves and calculates student information using a unique **Student ID**, reducing the need for repeated manual data entry.

### Analytical Question

> How can student academic performance and attendance data be transformed into a reliable, dynamic reporting system that supports faster and more consistent decision-making?

---

## Data

The dataset contains student-level information covering:

- Student identification and demographic information
- Subject scores
- Average academic performance
- Pass/Fail status
- Attendance
- Total school days
- Tuition information
- Class teacher information

The analysis used **Student ID `GA-2026088`** as the primary lookup key.

---

## Analytical Approach

The project combined dynamic data retrieval with calculated performance metrics.

### 1. Student Data Retrieval

Student information was dynamically retrieved using the Student ID. This allows the report card to update automatically when a different student identifier is entered.

### 2. Academic Performance Analysis

An average score was calculated across four core subjects:

| Subject | Score |
|---|---:|
| Mathematics | 88 |
| Science | 60 |
| English | 55 |
| Social Studies | 52 |
| **Average Score** | **63.8** |

### 3. Attendance Analysis

Attendance was calculated using the number of days present relative to total school days:

**117 ÷ 120 × 100 = 97.5%**

### 4. Performance Classification

A conditional rule was applied to determine the student's overall academic status.

**Result: PASS**

---

## Key Findings

### Strong Overall Performance

The student recorded an overall average score of **63.8**, resulting in a **PASS** classification.

### Mathematics Was the Strongest Subject

Mathematics recorded the highest score at **88**, making it the student's strongest subject among the four subjects analysed.

### English and Social Studies Require Attention

English (**55**) and Social Studies (**52**) recorded the lowest scores.

The difference between the highest score, Mathematics (**88**), and the lowest score, Social Studies (**52**), was **36 percentage points**, indicating substantial variation in subject-level performance.

### Attendance Was Strong

The student attended **117 of 120 school days**, resulting in an attendance rate of **97.5%**.

The strong attendance rate suggests that absenteeism is unlikely to be the primary explanation for the weaker performance in English and Social Studies. However, this interpretation is limited to the available student record and should not be generalized without cohort-level analysis.

---

## Business Insights

### 1. Aggregate Scores Can Hide Subject-Level Weaknesses

Although the student achieved a passing overall average, subject-level analysis revealed clear areas requiring academic attention.

This demonstrates the importance of analysing individual subject performance rather than relying solely on aggregate scores.

### 2. Dynamic Reporting Can Reduce Manual Work

Using Student ID-driven lookup and calculated fields allows student information and performance metrics to update automatically, reducing repetitive administrative data entry.

### 3. Attendance and Academic Performance Can Be Monitored Together

Combining attendance and academic indicators provides a broader view of student engagement and performance.

---

## Recommendations

### Targeted Academic Support

Provide additional academic support in **English and Social Studies**, while continuing to strengthen the student's performance in Mathematics.

### Automate Student Reporting

Extend the dynamic report card model to additional students and classes to reduce manual reporting effort and improve consistency.

### Develop Cohort-Level Analytics

The next phase could transform the individual report card into a school-wide dashboard for monitoring:

- Student performance
- Subject-level trends
- Attendance
- Pass rates
- Grade-level performance
- Students requiring academic intervention

---

## Project Outcome

The project demonstrates how structured student data can be transformed into a **dynamic reporting and decision-support solution** rather than a static report card.

The model allows users to enter a Student ID and automatically retrieve relevant student information, calculate academic and attendance metrics and determine the student's performance status.

---

## Skills Demonstrated

- Data cleaning and structuring
- Dynamic data lookup
- Calculated metrics
- Conditional logic
- Academic performance analysis
- Attendance analysis
- Business insight generation
- Data-driven recommendations
- Automated reporting design

---

## Key Metrics at a Glance

| Metric | Result |
|---|---:|
| Average Score | **63.8** |
| Performance Status | **PASS** |
| Highest Subject Score | **88 – Mathematics** |
| Lowest Subject Score | **52 – Social Studies** |
| Days Present | **117 / 120** |
| Attendance Rate | **97.5%** |

---

## Conclusion

The analysis shows that a dynamic, formula-driven reporting system can improve the efficiency and consistency of student performance reporting.

Beyond automating report generation, the model demonstrates how student-level data can be converted into actionable insights by combining **academic performance, attendance and business rules** in a single reporting workflow.
