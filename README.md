# 🏗️ Exploratory Data Analysis on Construction Projects

## 📊 Project Overview -

This project involves **Exploratory Data Analysis (EDA)** on a construction company’s project dataset consisting of **50+ projects across Indian cities**. The objective is to help the client (a builder) identify cost overruns, project delays, labor efficiency, and site risk patterns through data-driven insights.

## 🛠️ Technologies Used -

- 🐍 Python 3.x  
- 📦 Pandas  
- 📊 Matplotlib  
- 🧠 Seaborn  
- 🧾 Jupyter Notebook

## 📁 Dataset Information - 

It contains 50 records and the following fields:

- `Project Name` – Name/ID of the construction project  
- `Location` – City where the project is located  
- `Start Date`, `Planned End Date`, `Actual End Date` – Project schedule dates  
- `Planned Duration (days)`, `Actual Duration (days)` – Duration comparison  
- `Budget (INR)`, `Actual Cost (INR)` – Financial metrics  
- `Materials Used` – Key construction materials  
- `Average Daily Labor` – Labor force count per project  
- `Site Incidents` – Safety or operational incidents

## 🧼 Data Cleaning & Preparation -

- Removed special characters (`?`, `,`) from financial fields.
- Converted date columns into `datetime` format.
- Verified column data types using `.info()`.
- Checked for null values using `.isnull().sum()`.
- Performed descriptive statistics using `.describe()`.

## 📊 Visualizations & Insights -

### 1. 📍 Bar Plot – **Average Site Incidents by Location**
- Chennai and Hyderabad had the most site incidents.
  
### 2. ⏳ Histogram – **Actual Project Duration**
- Most projects lasted between **250 to 450 days**.

### 3. 👷 Histogram – **Average Daily Labor**
- Majority of projects used **40–70 workers daily**.

### 4. 🧱 Countplot – **Project Count by City**
- Hyderabad leads with the highest number of projects.

### 5. 📦 Boxplot – **Labor Distribution Across Locations**
- Wide variance in Chennai, low in Delhi (consistent).

### 6. 🔥 Heatmap – **Correlation Matrix**
- Found relationships between cost, duration, labor, and incidents.

### 7. 🥧 Pie Chart – **Project Distribution by Location**
- Hyderabad (20%) and Kolkata (18%) dominate project share.


## 📌 Conclusion -

This EDA provides the builder with:
- Better budgeting and scheduling strategies.
- City-wise performance benchmarking.
- Insights to reduce delays, manage costs, and allocate labor more efficiently.
