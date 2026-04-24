# Restaurant Rating Analysis & Prediction

### 🔷 Overview
This project performs an end-to-end **data analysis and machine learning pipeline** on a restaurant dataset.  

It focuses on extracting meaningful insights about customer preferences, pricing, cuisines, and location trends, and builds machine learning models to **accurately predict restaurant ratings based on structured features**.

---

### 🎯 Key Objectives
- Clean and preprocess real-world data
- Perform exploratory data analysis (EDA)
- Analyze geospatial and categorical patterns
- Engineer meaningful features
- Build regression models for rating prediction
- Generate insights through visualizations

---

### 📊 Dataset Features
The dataset includes:
- Restaurant Name
- City & Country Code
- Latitude & Longitude
- Cuisines
- Price Range
- Aggregate Rating -> (Target Variable)
- Votes
- Table Booking Availability
- Online Delivery Availability

---

### ⚙️ Project Workflow

**🔹 1. Data Exploration & Preprocessing**

- Checked dataset dimensions
- Handled missing values
- Converted data types
- Analyzed distribution of **Aggregate Rating**
- Identified class imbalance

---

**🔹 2. Descriptive Analysis**

- Calculated statistical measures (mean, median, std)
- Explored:
  - Cities 
  - Cuisines 
- Identified top-performing cities and cuisines

---

**🔹 3. Geospatial Analysis**

- Visualized restaurant locations using latitude & longitude
- Studied distribution across regions
- Analyzed relationship between **location and ratings**

---

**🔹 4. Price Range Insights**

- Identified most common price range
- Compared average ratings across price categories
- Observed trends between affordability and ratings

---

**🔹 5. Feature Engineering**

- Created:
  - `Has_Table_Booking`
  - `Has_Online_Delivery`
- Extracted features like:
  - Name length
  - Address length
- Encoded categorical variables

---

**🔹 6. Predictive Modeling**

Built regression models to predict restaurant ratings:
- Linear Regression
- Decision Tree
- Random Forest 

**Evaluation Metrics:**
- RMSE
- R² Score

---

**🔹 7. Customer Preference Analysis**

- Analyzed cuisine vs rating relationship
- Identified:
  - Most popular cuisines (based on votes)
  - High-rated cuisine categories

---

**🔹 8. Data Visualization**

- Histogram (rating distribution)
- Bar charts (city & cuisine comparison)
- Scatter plots (feature relationships)

---

### 📌 Key Insights
- Certain cuisines consistently receive higher ratings
- Mid-range price restaurants often perform better
- Online delivery increases engagement (votes)
- Location influences restaurant ratings

---

### 🛠️ Tech Stack
- Python 
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook
