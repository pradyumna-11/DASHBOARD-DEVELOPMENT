# DASHBOARD-DEVELOPMENT

"COMPANY" : CODTECH IT SOLUTIONS

"NAME" : SIKHAKOLLI PRADYUMNA

"INTERN ID" : CT08DN583

"DOMAIN" : DATA ANALYSIS

"DURATION" : 8 WEEKS

"MENTOR" : NEELA SANTOSH

## 📌 Task 3: Creating an Interactive Dashboard Using Dash, Power BI, or Tableau

### 📝 Overview

The objective of Task 3 is to build an **interactive data visualization dashboard** using modern tools such as **Dash (Python), Power BI, or Tableau**. Dashboards are crucial in data-driven environments as they allow stakeholders to explore key metrics, trends, and relationships within the data without needing to write code.

For this task, we used the **Titanic dataset**, a widely known dataset that includes passenger details such as age, gender, fare, survival status, and class. The goal was to design visualizations that enable users to interactively explore survival statistics based on demographic and economic features. The task was implemented in **three different tools** to highlight various strengths of each platform:

* **Dash**: a Python-based web framework for building data apps
* **Power BI**: a Microsoft tool for drag-and-drop analytics
* **Tableau Public**: a popular platform for visual analytics

---

### ⚙️ Tools & Technologies

* **Python 3** + **Dash (Plotly)**
* **Power BI Desktop**
* **Tableau Public**
* **Pandas, Plotly Express, and Seaborn** (for processing and plotting in Dash)
* **Google Colab** (for Dash deployment using `pyngrok`)

---

### 🎯 Purpose

The dashboard helps answer the following questions:

* What is the survival rate based on gender?
* How does passenger class affect survival probability?
* What’s the distribution of fare across different age groups?
* Can users dynamically filter data to uncover specific insights?

Dashboards turn static data into dynamic insights, making it easier for both technical and non-technical users to interpret trends and patterns.

---

### 🧱 Implementation Details

#### 🔹 1. Dash (Python-Based Dashboard)

A full web-based interactive dashboard was developed using Dash, which provides:

* A **dropdown filter** for selecting gender
* **Bar charts** showing survival rate and passenger class distribution
* **Scatter plot** of Fare vs Age, colored by survival status

The app was deployed via `pyngrok` on Google Colab for easy sharing and public access. Callback functions in Dash were used to dynamically update graphs based on user input.

#### 🔹 2. Power BI

Power BI was used to create a clean, interactive dashboard without coding:

* Loaded Titanic dataset in `.csv` format
* Created slicers for gender and class filters
* Added pie chart, bar chart, and scatter plot visualizations
* The dashboard allowed drag-and-drop rearrangement and real-time filtering

The `.pbix` file can be shared or exported to PDF for submission.

#### 🔹 3. Tableau Public

Tableau allowed for rapid visualization building:

* Imported the dataset and cleaned it using Tableau’s data prep interface
* Designed a dashboard with filters and visual elements
* Published the dashboard to Tableau Public for web access

---

### 📊 Insights Gained

* Female passengers had a significantly higher survival rate than males.
* First-class passengers were more likely to survive compared to second and third-class passengers.
* Higher ticket fares correlated with higher survival chances.
* Age had a slight influence, especially for younger children and older passengers.

These insights became immediately clear through dynamic visualizations and interactive filtering.

---

### 📤 Deliverables

* A Python `.ipynb` notebook (for Dash version)
* `app.py` file (for standalone execution)
* `.pbix` file (for Power BI version)
* Tableau `.twbx` file or public dashboard link
* Screenshots or video demo of all three versions

---

### 🚀 Conclusion

This task demonstrated the importance of data visualization tools in interpreting complex datasets. Each platform—Dash, Power BI, and Tableau—has unique strengths:

* **Dash** allows full customization with Python code
* **Power BI** is quick and business-user friendly
* **Tableau** offers clean visuals and fast interactive layouts

By completing this task in all three tools, we explored the versatility of modern dashboarding technologies and enhanced the presentation of data insights.
