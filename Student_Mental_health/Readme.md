# 🧠 Student Mental Health Analysis  
A complete Exploratory Data Analysis (EDA) project based on a **100,000-record dataset** of students, focusing on identifying patterns in **depression, anxiety, panic attacks**, and **help-seeking behavior**.

---

## 📌 Project Overview
This project analyzes mental health patterns among students using demographic and academic attributes such as:

- Gender  
- Age  
- Course & Year of Study  
- CGPA Range  
- Marital Status  
- Depression  
- Anxiety  
- Panic Attacks  
- Treatment Seeking Behavior  

The goal is to understand how different factors contribute to mental health challenges among students.

---

## 📁 Dataset Description

### **Columns in the Dataset**

| Column Name | Description |
|------------|-------------|
| **Timestamp** | Date when the response was recorded |
| **Choose your gender** | Gender of the student (Male/Female/Others) |
| **Age** | Age of the student |
| **What is your course?** | Course enrolled by the student |
| **Your current year of study** | Year 1, Year 2, Year 3, Year 4 |
| **What is your CGPA?** | CGPA range (e.g., 3.00–3.49, 2.50–2.99, etc.) |
| **Marital status** | Married/Single |
| **Do you have Depression?** | Yes/No |
| **Do you have Anxiety?** | Yes/No |
| **Do you have Panic attack?** | Yes/No |
| **Did you seek any specialist for treatment?** | Yes/No |

> ✔ Data file is available in the `data/` folder.

---

## 🎯 Problem Statement
Mental health issues among students are increasing.  
This project attempts to explore:

- Which students are more likely to report **depression**, **anxiety**, or **panic attacks**?  
- Do academic factors like **CGPA** or **Year of Study** influence mental health?  
- Are students actually **seeking help** when they experience symptoms?  
- Which demographic groups are at higher risk?

---

## 🎯 Objectives
✔ Perform complete EDA on the student mental health dataset  
✔ Understand distributions and patterns  
✔ Analyze relationships between demographics and mental health  
✔ Visualize mental health patterns across gender, course, CGPA, and study year  
✔ Summarize insights that institutions can use for mental health programs  

---

## 🛠 Tools & Technologies
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Jupyter Notebook / VS Code**

---

## 📊 EDA Steps & Visualizations Included
Your project includes:

### **1️⃣ Data Cleaning**
- Handling missing values  
- Converting Yes/No to numeric (0/1)  
- Standardizing CGPA ranges  
- Converting age into numeric  
- Creating “Risk Score” (optional)

---

### **2️⃣ Univariate Analysis**
- Gender count  
- Marital status distribution  
- Depression/Anxiety/Panic Attack frequency  
- Year-wise distribution  
- CGPA distribution  

---

### **3️⃣ Bivariate Analysis**
#### 📌 Gender vs Mental Health  
- Depression Count  
- Anxiety Count  
- Panic Attacks  

#### 📌 CGPA vs Mental Health  
- Low CGPA students show higher issues  
- Boxplots with median & IQR  

#### 📌 Year of Study vs Depression/Anxiety  
- Year 1 & Year 3 show higher stress indicators  

#### 📌 Course-wise Mental Health  
- Engineering, Psychology, Medical show higher indicators  

---

### **4️⃣ Key Visualizations**
(From your notebook and charts)

- Histogram of depression, anxiety & panic attack distribution  
- Boxplots with median and IQR annotations  
- Gender comparison bar charts  
- CGPA vs Depression bar plot  
- Year-wise mental health bar chart  
- Course-wise heatmap (optional)  

---

## ⭐ Key Insights (Based on Your Analysis)

✔ Students in **Year 1 and Year 3** show highest mental health issues.  
✔ Females reported **more anxiety**, while males reported a slightly higher rate of **depression**.  
✔ Students with **low CGPA (below 3.0)** tend to show elevated mental health challenges.  
✔ Panic attacks are common among students who already have anxiety.  
✔ A large number of students **did not seek treatment**, even when reporting depression/anxiety.  
✔ Courses like **Engineering, Psychology, Medical** show more stress symptoms.

---

## 📂 Folder Structure
## 📂 Project Files

| File / Folder | Description |
|---------------|-------------|
| `data/student_mental_health.csv` | Original dataset containing 100,000 student records |
| `notebook/Student_Mental_Health_Analysis.ipynb` | Jupyter notebook with complete EDA and visualizations |
| `visuals/` | Folder containing all generated charts and plots |
| `README.md` | Project documentation |
| `requirements.txt` | Python dependencies required to run the project |

## 👤 Author
Name: Muthulaxmi Lakhani  
Role: Data Analysis / Student Project  
Project: Student Mental Health Analysis  
Tools: Python, Pandas, Matplotlib, Seaborn  



