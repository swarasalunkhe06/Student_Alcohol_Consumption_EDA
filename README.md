# 🎓 Student Alcohol Consumption – Exploratory Data Analysis (EDA)

### Understanding Student Drinking Habits, Lifestyle Patterns, and Their Relationship with Academic Performance

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on student alcohol consumption patterns using two datasets: Mathematics (`student-mat.csv`) and Portuguese (`student-por.csv`).

The analysis explores how students' demographic characteristics, social behaviour, family background, study habits, and lifestyle choices relate to weekday and weekend alcohol consumption and academic performance.

The project uses Python and its data analysis and visualization libraries to identify patterns, trends, and relationships within the datasets.

## 🎯 Project Objectives

- Analyze student demographics, including age and gender distribution.
- Compare weekday and weekend alcohol consumption.
- Investigate the relationship between alcohol consumption and academic performance.
- Explore the influence of social activities and free time on drinking habits.
- Analyze family background and parental education.
- Examine the relationship between study time, attendance, health, and academic performance.
- Compare Mathematics and Portuguese students' academic performance.

## 📂 Dataset Information

The project uses two CSV datasets:

| Dataset | Description | Records |
|---|---|---:|
| `student-mat.csv` | Mathematics students | 395 |
| `student-por.csv` | Portuguese students | 649 |

Each dataset contains 33 columns covering student demographics, family information, lifestyle habits, alcohol consumption, and academic grades.

### Important Features

| Feature | Description |
|---|---|
| `age` | Student's age |
| `sex` | Student's gender |
| `studytime` | Weekly study time |
| `goout` | Going out with friends |
| `freetime` | Amount of free time |
| `Dalc` | Weekday alcohol consumption |
| `Walc` | Weekend alcohol consumption |
| `health` | Current health status |
| `absences` | Number of school absences |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade |

**Alcohol Consumption Scale:**

1 = Very Low  
2 = Low  
3 = Moderate  
4 = High  
5 = Very High

## 🛠️ Technologies & Libraries Used

- **Python** – Primary programming language
- **NumPy** – Numerical operations
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive analysis environment

## 🔍 Exploratory Data Analysis

The project covers the following analyses:

### 1. Data Understanding & Preprocessing
- Dataset dimensions and structure.
- Data types and statistical summaries.
- Missing value detection.
- Duplicate record detection.
- Data preprocessing and validation.

### 2. Student Demographics
- Age distribution.
- Gender distribution.
- Mathematics and Portuguese student comparisons.

### 3. Alcohol Consumption Analysis
- Weekday vs. weekend alcohol consumption.
- Consumption patterns across different alcohol levels.

### 4. Academic Performance Analysis
- Final grade distribution.
- Alcohol consumption vs. academic performance.
- Average grades across different consumption levels.
- Mathematics vs. Portuguese grade comparison.

### 5. Social Behaviour Analysis
- Going out with friends vs. weekend alcohol consumption.
- Free time vs. weekday alcohol consumption.
- Romantic relationships vs. academic performance.

### 6. Family Background Analysis
- Mother's education vs. final grades.
- Family relationship quality vs. academic performance.

### 7. Health & Attendance Analysis
- School absences vs. final grades.
- Health status vs. weekend alcohol consumption.

### 8. Study Habits Analysis
- Study time vs. weekend alcohol consumption.
- Age vs. weekday alcohol consumption.

## 📊 Key Findings & Insights

1. **Student Demographics:** Both datasets primarily contain students between 15 and 18 years of age.

2. **Weekend Drinking:** Weekend alcohol consumption is generally higher than weekday consumption across both datasets.

3. **Academic Performance:** Mathematics students show no clear linear relationship between weekday alcohol consumption and final grades.

4. **Portuguese Academic Performance:** Higher alcohol consumption, particularly on weekends, is associated with lower average final grades.

5. **Social Behaviour:** Students who spend more time going out with friends tend to report higher weekend alcohol consumption.

6. **Free Time:** Students reporting more free time tend to show higher average weekday alcohol consumption.

7. **Family Background:** Parental education and family relationship quality show variations in academic performance, but no consistent strong relationship.

8. **Study Habits:** Students with more study time generally report lower weekend alcohol consumption.

9. **Subject Comparison:** Portuguese students demonstrate higher average final grades than Mathematics students in the analyzed datasets.

*Note: These findings represent observed associations in the datasets and do not establish causal relationships.*

## ⚙️ Installation & Setup

### Prerequisites

Make sure Python 3.x and Jupyter Notebook are installed on your system.

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/student-alcohol-consumption-eda.git
```

### Step 2: Navigate to the Project Directory

```bash
cd student-alcohol-consumption-eda
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Step 4: Add the Dataset Files

Place both CSV files in the project directory:

```text
student-mat.csv
student-por.csv
```

### Step 5: Update Dataset Paths

Make sure the notebook reads the CSV files using relative paths:

```python
math = pd.read_csv("student-mat.csv")
portuguese = pd.read_csv("student-por.csv")
```

### Step 6: Run Jupyter Notebook

```bash
jupyter notebook
```

Open `Student_Alcohol_Consumption_EDA.ipynb` and execute the notebook cells.

## 📁 Project Structure

```text
Student-Alcohol-Consumption-EDA/
│
├── Student_Alcohol_Consumption_EDA.ipynb
│
├── student-mat.csv
│
├── student-por.csv

```

## 🎨 Visualization

The project includes multiple visualizations, such as:

- Count plots
- Pie charts
- Bar charts
- Histograms
- Scatter plots
- Heatmaps
- Violin plots

These visualizations help identify patterns and relationships between student behaviour, alcohol consumption, and academic performance.

## 🏁 Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand student lifestyle patterns and their relationship with academic outcomes.

By analyzing Mathematics and Portuguese student datasets, the project identifies differences in weekday and weekend alcohol consumption and explores how social, family, and study-related factors are associated with academic performance.

The project provides practical experience in data cleaning, statistical exploration, data visualization, and extracting meaningful insights using Python.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Data Analytics  
**Language:** Python  
**Environment:** Jupyter Notebook
