# 💡 Global Tech Trends and Developer Insights 2024

A data analysis and visualization project aimed at uncovering global developer trends in programming languages, databases, compensation, and work preferences using real-world survey data.

---

## 📌 Project Overview

This project analyzes responses from the Stack Overflow Developer Survey 2024 to:

- Identify current and future trends in programming languages and databases
- Understand developer job satisfaction and compensation
- Visualize demographics and remote work preferences
- Build interactive dashboards for stakeholder-friendly insights

---

## 📂 Dataset Information

- **Source**: Stack Overflow Developer Survey 2024
- **Format**: CSV / SQLite database
- **Size**: ~90,000+ rows
- **Key Columns**:
  - `LanguageHaveWorkedWith`
  - `LanguageWantToWorkWith`
  - `DatabaseHaveWorkedWith`
  - `DatabaseWantToWorkWith`
  - `JobSat`
  - `YearsCodePro`
  - `ConvertedCompYearly`
  - `RemoteWork`
  - `EdLevel`
  - `Age`

---

## 🧰 Tools & Technologies Used

- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **SQLite3** for querying survey database
- **IBM Cognos Analytics** and **Google Looker Studio** for dashboards
- **Jupyter Notebook** for data wrangling and analysis
- **PowerPoint Online** for presentation

---

## ⚙️ Project Workflow

1. **Data Cleaning & Preprocessing**  
   - Handled missing values and outliers  
   - Parsed multiselect fields into individual entries  
   - Mapped age groups to numeric values  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of coding experience (`YearsCodePro`)  
   - Comparison of `LanguageHaveWorkedWith` vs `LanguageWantToWorkWith`  
   - Box plots and histograms for `Age` and `ConvertedCompYearly`  
   - Correlation heatmaps for numeric variables  

3. **Dashboard Creation**  
   - Built interactive dashboards using IBM Cognos Analytics and Google Looker Studio  
   - Created views for:
     - Current Technology Usage
     - Future Technology Trends
     - Demographics & Education

4. **Visualization & Presentation**  
   - PowerPoint presentation with visual insights and findings  
   - Included dashboard screenshots, bar charts, scatter plots, and trend graphs

---

## 📊 Key Visualizations

- Bar charts: Top 10 programming languages and databases (current vs future)
- Venn diagram: Overlap in languages used vs wanted
- Box plot: Age distribution
- Correlation heatmap: Age, compensation, and satisfaction
- Scatter plot: Age vs WorkExp
- Histograms: Compensation across age groups

---

## 🧠 Insights

- **Python**, **JavaScript**, and **SQL** are most used; **Rust** and **TypeScript** are gaining popularity  
- **PostgreSQL** and **MongoDB** lead in future database preferences  
- Developers with more experience report higher job satisfaction  
- Majority prefer hybrid/remote work setups  
- Median compensation increases with professional experience  

---

## 📈 Dashboards

The project includes three main dashboards:

1. **Current Technology Usage**  
   Visualizes tools, languages, databases, and platforms respondents currently use

2. **Future Technology Trends**  
   Shows desired technologies, platforms, and tools developers aim to learn

3. **Demographics**  
   Displays breakdowns by age group, education level, gender, and region

---

## 📄 Presentation

A PowerPoint presentation summarizes:

- Project purpose, methodology, and tools  
- Programming and database trends  
- Key findings from dashboards  
- Implications and conclusions  

📎 _Presentation link available in the repo: [View Presentation](./presentation.pdf)_

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tech-trends-analysis.git
   cd tech-trends-analysis
