# 🎓 Student Performance Prediction & Power BI Dashboard

This project focuses on analyzing student performance using **machine
learning models** in Google Colab and creating a **Power BI dashboard**
for interactive visualization.

------------------------------------------------------------------------

## 📌 Aim

To predict student performance based on academic and personal factors
using ML models and to visualize insights through a Power BI dashboard.

------------------------------------------------------------------------

## 🧑‍💻 Part 1: Machine Learning (Google Colab)

-   **Dataset Used**: Student performance dataset with columns like
    gender, study time, parental education, scores, etc.\
-   **Steps Performed**:
    1.  Data Cleaning and Preprocessing\
    2.  Exploratory Data Analysis (EDA)\
    3.  Feature Selection & Encoding\
    4.  Model Training (Linear Regression, Random Forest, XGBoost)\
    5.  Model Evaluation with Accuracy, MAE, RMSE\
    6.  Final Insights

**Conclusion**:\
XGBoost performed best among the models, providing accurate predictions
on student scores. The study time, parental support, and attendance
strongly influenced performance.

------------------------------------------------------------------------

## 📊 Part 2: Power BI Dashboard

The dashboard is designed in **4 pages**:

### Page 1: KPIs & Overview

-   Total Students\
-   Average Score\
-   Pass %\
-   Gender Distribution\
-   Visuals: KPI Cards + Pie Chart

![DashBoard 1]<img width="1287" height="739" alt="DashBoard 1" src="https://github.com/user-attachments/assets/4ecc659a-5d8f-4c6f-866c-3075bcf4d28c" />



------------------------------------------------------------------------

### Page 2: Performance by Factors

-   Bar Chart (Scores by Gender)\
-   Pie Chart (Parental Education Impact)\
-   Column Chart (Study Time vs Scores)\
-   Stacked Bar (Absences vs Performance)

![DashBoard 2]<img width="1252" height="720" alt="DashBoard 2" src="https://github.com/user-attachments/assets/de8e35d7-d47c-4748-840f-fc5d6aba6157" />


------------------------------------------------------------------------

### Page 3: Score Distribution

-   Histogram of Scores\
-   Line/Combo Chart for Trend\
-   Box Plot for Score Spread

![DashBoard 3]<img width="1242" height="738" alt="DashBoard 3" src="https://github.com/user-attachments/assets/3d11847e-98fd-4111-bbcf-94b29542ab4a" />


------------------------------------------------------------------------

### Page 4: Attendance & Study Habits

-   Line Chart (Absences Trend)\
-   Bar Chart (Study Time vs Scores)\
-   Scatter Plot (Attendance vs Performance)

![DashBoard 4]<img width="1297" height="738" alt="DashBoard 4" src="https://github.com/user-attachments/assets/31ebcf9d-a9f7-4112-a937-e6c41ad6e8c3" />


------------------------------------------------------------------------

## 📂 Project Structure

    Student_Performance_Project/
    │── Student_Performance_Colab.ipynb   # ML code in Google Colab
    │── PowerBI_Dashboard.pbix            # Power BI file
    │── README.md                         # Documentation
    │── images/                           # Dashboard screenshots
    │    ├── page1.png
    │    ├── page2.png
    │    ├── page3.png
    │    └── page4.png

------------------------------------------------------------------------

## 🚀 How to Use

1.  **Google Colab Notebook**
    -   Open `Student_Performance_Colab.ipynb` in Colab\
    -   Run all cells to preprocess, train, and evaluate models
2.  **Power BI Dashboard**
    -   Open `PowerBI_Dashboard.pbix` in Power BI Desktop\
    -   Explore 4 interactive pages

------------------------------------------------------------------------

## 📌 Conclusion

-   **ML Models**: Provided accurate prediction of student performance.\
-   **Power BI Dashboard**: Helped visualize key factors like gender,
    study time, parental education, and attendance.\
-   **End Goal**: Assist educators and parents in understanding and
    improving student performance.

------------------------------------------------------------------------

✨ *Developed by Sri Venkata Satyanarayana Gattu*
