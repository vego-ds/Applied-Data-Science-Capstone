# Applied Data Science Capstone: SpaceX Falcon 9 Landing Prediction

## Project Overview

This repository contains the final capstone project for the Applied Data Science program. The project focuses on analyzing SpaceX Falcon 9 launch data to predict whether the first stage booster will successfully land and be reused.

The project follows the complete data science lifecycle including:
- Data collection
- Data wrangling
- Exploratory data analysis (EDA)
- SQL analysis
- Interactive visual analytics
- Predictive modeling
- Dashboard development
- Presentation of findings

---

## Business Problem

SpaceX significantly reduces launch costs through reusable Falcon 9 boosters. Predicting first stage landing success helps estimate launch costs and supports strategic decision-making for competing aerospace companies.

The objective of this project is to build machine learning models capable of predicting Falcon 9 first stage landing outcomes using publicly available launch data.

---

## Data Sources

The project uses publicly available data from:
- SpaceX REST API
- Wikipedia Falcon 9 launch records
- Web scraping techniques using BeautifulSoup

---

## Technical Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Folium
- Scikit-learn
- SQL
- Dash

---

## Project Structure

```bash
├── notebooks/
│   ├── data_collection_api.ipynb
│   ├── web_scraping.ipynb
│   ├── data_wrangling.ipynb
│   ├── eda_sql.ipynb
│   ├── eda_visualization.ipynb
│   ├── folium_maps.ipynb
│   ├── dashboard_application.py
│   └── predictive_analysis.ipynb
│
├── presentation/
│   └── Applied_Data_Science_Capstone.pdf
│
├── README.md
└── requirements.txt
```

---

## Methodology

### 1. Data Collection
- Collected SpaceX launch data using REST API
- Extracted launch records through web scraping

### 2. Data Wrangling
- Cleaned missing values
- Filtered Falcon 9 launches
- Created target classification labels

### 3. Exploratory Data Analysis
- Launch success trends
- Payload analysis
- Orbit analysis
- Launch site comparison
- SQL-based insights

### 4. Interactive Visual Analytics
- Folium geographic launch maps
- Plotly Dash dashboard

### 5. Predictive Analysis
Machine learning models implemented:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

Model performance evaluated using:
- Accuracy Score
- GridSearchCV
- Confusion Matrix

---

## Key Insights

- Launch success rates improved significantly over time
- Payload mass and launch site strongly influence landing success
- Certain orbit types correlate with higher recovery rates
- Machine learning models can effectively predict landing outcomes

---

## Results

The final predictive model achieved strong classification performance in predicting Falcon 9 first stage landing success using launch configuration and mission-related variables.

---

## Dashboard

Interactive dashboard developed using Plotly Dash for:
- Launch site analytics
- Payload range filtering
- Success rate visualization


---

## Final Deliverables

- Jupyter notebooks
- Interactive dashboard
- Data visualizations
- Machine learning models
- Final presentation PDF

---

## Author
Venkatram Gogineni

---

## License
This project is for educational purposes as part of the Applied Data Science Capstone program.
