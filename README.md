# Patient Appointment No-Show Analysis

A comprehensive healthcare data analytics project that explores the factors influencing missed medical appointments (No-Shows). Using Python for data cleaning, feature engineering, exploratory data analysis (EDA), and statistical analysis, this project identifies key patterns that can help healthcare providers reduce missed appointments, improve clinic efficiency, and optimize patient scheduling.

---

## Project Overview

Missed healthcare appointments reduce clinical efficiency, increase operational costs, and delay care for other patients. This project analyzes patient appointment records to uncover the characteristics and behaviors associated with appointment attendance.

The analysis focuses on identifying patterns related to:

* Patient demographics
* Waiting time before appointments
* Appointment scheduling
* SMS reminders
* Existing medical conditions
* Attendance behavior

The findings can support healthcare organizations in developing targeted interventions to reduce no-show rates.

---

##  Business Problem

Healthcare facilities lose valuable resources when patients fail to attend scheduled appointments.

This project aims to answer questions such as:

* Which patients are more likely to miss appointments?
* Does waiting time affect attendance?
* Are SMS reminders associated with better attendance?
* Which appointment days experience the highest no-show rates?
* What patient characteristics are associated with missed appointments?

---

## Dataset

The dataset contains patient appointment records with demographic, clinical, and scheduling information.

### Key Variables

| Variable        | Description                                  |
| --------------- | -------------------------------------------- |
| Age             | Patient age                                  |
| Gender          | Patient gender                               |
| Scholarship     | Government welfare support                   |
| Hypertension    | Hypertension diagnosis                       |
| Diabetes        | Diabetes diagnosis                           |
| Alcoholism      | Alcohol use indicator                        |
| Handicap        | Disability indicator                         |
| SMS Received    | Whether an SMS reminder was received         |
| Scheduled Day   | Date appointment was scheduled               |
| Appointment Day | Appointment date                             |
| No-show         | Whether the patient attended the appointment |

---

##  Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

##  Project Workflow

### 1. Data Quality Assessment

The dataset was examined for:

* Missing values
* Duplicate records
* Incorrect data types
* Invalid values
* Inconsistent category labels

---

### 2. Data Cleaning

Cleaning tasks included:

* Correcting data types
* Removing inconsistencies
* Standardizing categorical variables
* Preparing the dataset for analysis

---

### 3. Feature Engineering

Additional analytical features were created, including:

* Age grouping
* Waiting time calculation
* Waiting time categories
* Appointment weekday extraction
* Attendance indicator formatting

---

### 4. Exploratory Data Analysis (EDA)

#### Univariate Analysis

Explored the distribution of:

* Appointment status
* Age
* Gender
* Appointment day
* Waiting time
* SMS reminders

#### Bivariate Analysis

Investigated relationships between:

* Age vs Appointment Status
* Waiting Time vs Appointment Status
* Appointment Day vs Attendance
* SMS Reminder vs Attendance
* Age Group vs Attendance
* Waiting Time Category vs Attendance

---

### 5. Statistical Analysis

Performed statistical analysis including:

* Correlation analysis
* Identification of meaningful relationships between variables
* Interpretation of patterns influencing appointment attendance

---

##  Key Insights

The analysis identified several important trends:

* Longer waiting times were associated with increased appointment no-shows.
* Attendance patterns varied across appointment weekdays.
* Certain age groups exhibited higher no-show rates than others.
* SMS reminders alone did not completely eliminate missed appointments.
* Patient demographics and scheduling characteristics jointly influenced attendance behavior.

---

## 💡 Recommendations

Based on the analysis, healthcare providers should consider:

* Reducing waiting time between scheduling and appointments.
* Sending multiple reminder notifications rather than a single SMS.
* Prioritizing high-risk patients for follow-up communication.
* Optimizing appointment scheduling for days with historically lower attendance.
* Developing predictive models to identify patients at high risk of missing appointments.


---

## 👤 Author

**Michael Omojokun**

Healthcare Data Analyst | Dentist | MPH Candidate

**Skills:** Python • SQL • Power BI • Excel • Healthcare Analytics • Data Visualization
