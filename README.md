# student-mental-health-analytics
PostgreSQL data analysis on modern university student mental health trends, investigating academic burnout factors
# Student Mental Health Analytics: PostgreSQL Insights

## 📌 Project Overview
This project investigates the academic and demographic factors contributing to depression and anxiety among modern university students. Using structured data and PostgreSQL queries, the analysis looks beyond traditional "international adjustment" studies to identify how specific fields of study and cumulative academic burnout affect mental health trends over time.

## 📊 The Dataset
The analysis utilizes a student survey dataset tracking variables such as:
* **Demographics**: Field of study (course), current year of enrollment, and gender.
* **Psychometric Factors**: Self-reported indicators for Depression, Anxiety, and Panic Attacks.
* **Lifestyle Factors**: Marital status and current CGPA metrics.

## 🛠️ Technologies Used
* **Database Engine**: PostgreSQL syntax executed via DuckDB
* **Development Environment**: Google Colab / Jupyter Notebooks
* **Data Handling**: Python Pandas (for file loading and initial table registration)

## 💡 Key Insights
* **High-Stress Academic Fields**: Students enrolled in highly intensive technical disciplines—specifically **Engineering and Computer Science**—demonstrated disproportionately higher rates of self-reported anxiety and depression compared to humanities tracks.
* **The Longevity Factor**: Mental health risks did not peak during initial university enrollment. Instead, depression and anxiety rates remained consistently high or **escalated during the 2nd and 3rd years** of study, implying that cumulative academic burnout is a major contributing factor.

## 🚀 How to Run the Project
1. Open the `student_mental_health_analytics.ipynb` file directly in GitHub to view the code.
2. Alternatively, clone this repository and upload the `.ipynb` notebook and `student_mental_health.csv` file into Google Colab.
3. Run the environment setup cell to query the data locally via SQL.
