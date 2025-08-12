# 📊 911 Calls Data Analysis

This project analyzes **911 emergency call data** to find trends in reasons for calls, peak hours, and patterns across days and months.  
It uses **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** for data processing and visualization.

---

## 📌 Features
- Data loading and cleaning
- Time-based feature extraction (Hour, Month, Day of Week)
- Visualization of call reasons
- Trend analysis over time
- Heatmaps and clustering

---

## 📂 Dataset
The dataset contains 911 call records with details such as:
- `timeStamp` — Date and time of the call  
- `title` — Reason for the call  
- `lat` & `lng` — Location coordinates  
- `zip` & `twp` — Zipcode and township  

---

## 📈 Visualizations

### 1. Calls per Month
![Calls per Month](Call Capston Project image 5)

### 2. Monthly Trend (Regression)
![Monthly Trend](7cebbc2e-0563-4479-9256-a44c01d9895d.png)

### 3. Fire Calls Over Time
![Fire Calls Over Time](b58f19fe-89ef-4da4-a333-8346fa529eff.png)

### 4. Heatmap: Day of Week vs Month
![Heatmap](d6ff734d-cbc6-451c-8abe-9b94b9b9f78c.png)

### 5. Monthly Calls by Reason
![Monthly Calls by Reason](97163b1e-be57-4588-a124-b96548efc2d0.png)

---

## 🛠 Technologies Used
- **Python 3.x**
- **Pandas** — Data manipulation
- **NumPy** — Numerical computing
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical plotting

---

## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/yourusername/911-calls-analysis.git

# Navigate to the project folder
cd 911-calls-analysis

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
