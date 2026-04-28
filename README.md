# 📊 Machine Learning and Spatial Analysis of Service Adequacy  
### Demographic Typology and Education–Health Service Analysis of GN Divisions in Uva Province, Sri Lanka

---

## 📌 Project Overview

This project aims to analyze demographic patterns and evaluate the adequacy of education and healthcare services at the **Grama Niladhari (GN) division level** in Uva Province, Sri Lanka.

The study integrates **data science, machine learning, and spatial analysis** to identify areas where public services may not sufficiently meet population needs.

---

## 🎯 Objectives

- Analyze GN-level demographic structure (children, working-age, elderly)
- Identify variation in population composition across GN divisions
- Evaluate accessibility to schools and healthcare facilities
- Detect potential service mismatch areas (high demand vs low access)
- Apply machine learning techniques:
  - K-means clustering (demographic typology)
  - Classification models (service adequacy prediction)

---

## 📂 Datasets Used

### 1. Population Dataset
- GN Code, GN Name, District
- Total Population
- Age groups:
  - 0–14 (Children)
  - 15–59 (Working age)
  - 60–64, 65+ (Elderly)

### 2. Accessibility Data
- Distance to nearest school (km)
- Distance to nearest hospital (km)

### 3. Spatial Data
- GN boundary shapefile
- School locations
- Hospital locations

---

## ⚙️ Methodology

### 🔹 1. Data Preprocessing
- Data cleaning and validation
- Handling missing values
- Standardizing GN-level data

### 🔹 2. Feature Engineering
- Population proportions:
  - Children %
  - Working %
  - Elderly %
- Dependency ratio calculation
- Accessibility indicators

### 🔹 3. Exploratory Data Analysis (EDA)
- Distribution analysis of demographic variables
- Accessibility analysis (distance distributions)
- Identification of hotspot GN divisions
- District-level comparisons (Badulla vs Monaragala)

### 🔹 4. Clustering (Unsupervised ML)
- K-means clustering
- Input features:
  - p_children, p_working, p_elderly, dependency_ratio
- Output:
  - Demographic typology (cluster labels)

### 🔹 5. Service Adequacy Modeling
- Education adequacy:
  - Schools per 1000 children
- Health adequacy:
  - Facilities per 1000 elderly
- Quantile-based threshold labeling

### 🔹 6. Predictive Modeling (Supervised ML)
- Models:
  - Logistic Regression
  - Random Forest
- Input features:
  - Demographic + accessibility + cluster data
- Output:
  - Adequate / Inadequate classification

### 🔹 7. Spatial Analysis
- Mapping GN-level results using QGIS / GeoPandas
- Visualization of:
  - Clusters
  - Accessibility
  - Service adequacy

---

## 📊 Key Findings (EDA Stage)

- Significant variation exists in demographic composition across GN divisions
- Monaragala district shows higher average distances to services
- Some GN divisions exhibit high population demand with low accessibility
- Potential service gaps are more evident in rural areas

---

## 🧠 Machine Learning Components

### 1. Clustering (Unsupervised)
- Algorithm: K-means
- Purpose: Identify demographic patterns

### 2. Classification (Supervised)
- Algorithms:
  - Logistic Regression
  - Random Forest
- Target:
  - Service adequacy label (0 = adequate, 1 = inadequate)

---

## 🗺️ Tools and Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib / Seaborn
- GeoPandas
- QGIS
- Jupyter Notebook / Google Colab

---

## 📈 Outputs

- Cleaned GN-level dataset
- Demographic indicators
- Cluster classifications
- Service adequacy labels
- Machine learning model results
- Spatial maps

---

## 🚧 Project Status

- ✅ Data collection completed
- ✅ Data preprocessing completed
- ✅ Exploratory Data Analysis completed
- 🔄 Clustering and modeling in progress
- 🔄 Spatial analysis refinement ongoing

---

## ⚠️ Limitations

- GN-level facility counts may be approximated
- Accessibility measured using distance (not travel time)
- Cross-sectional data (no temporal variation)

---

## 📌 Future Work

- Improve feature set with finer age segmentation
- Enhance model performance with additional variables
- Incorporate travel time-based accessibility
- Develop policy recommendation framework

---

## 👨‍💻 Author

Final Year Undergraduate  
BSc in Data Science  

---

## 📜 License

This project is for academic and research purposes only.
