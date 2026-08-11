<h1 align="center">Python Data Analysis & Geospatial Analytics (843K+ Records)</h1>

This repository showcases an end-to-end **Python data analysis and geospatial analytics project** built using over **843,000 Los Angeles crime records**. The project follows a structured analytical workflow from raw data ingestion and preprocessing through statistical analysis, geospatial visualization, and insight generation.

Although the project uses **Los Angeles crime data** as its case study, the techniques demonstrated such as **data cleaning, exploratory data analysis (EDA), feature engineering, statistical testing, geospatial analysis, interactive visualization, and large-scale data processing** are broadly transferable across business intelligence, public sector analytics, finance, healthcare, operations, and other data-driven domains.

Using **Python**, **pandas**, **NumPy**, **Matplotlib**, **Plotly**, **Folium**, **SciPy**, and **Jupyter Notebook**, the project transforms over **180 MB** of raw public data into reproducible analytical workflows and interactive visualizations that reveal temporal, demographic, and geographic crime patterns.

The project concludes with an interactive Jupyter Notebook presenting statistical analyses, geospatial heatmaps, and visual dashboards that communicate key public safety insights through clear, data-driven storytelling.

# 🎯 Project Goals

The project was designed to analyze large-scale public crime data using reproducible Python workflows to identify meaningful temporal, demographic, and geographic crime patterns.

The primary objectives were to:

- Clean and preprocess over **843,000** crime records.
- Perform exploratory data analysis (EDA).
- Engineer features for temporal and demographic analysis.
- Identify long-term crime trends and seasonal patterns.
- Analyze crime distributions across Los Angeles.
- Visualize geographic crime hotspots using interactive maps.
- Validate analytical findings using statistical hypothesis testing.
- Communicate insights through clear visualizations and data storytelling.

# 🏗️ Solution Architecture

### Workflow

```text
Raw LAPD Crime Dataset
            ↓
Data Cleaning & Preprocessing
            ↓
Feature Engineering
            ↓
Exploratory Data Analysis (EDA)
            ↓
Statistical Testing
            ↓
Geospatial Analysis
            ↓
Interactive Visualization
            ↓
Analytical Insights
```

### Data

- **Primary Dataset:** Los Angeles Crime Data (2020–Present)
- **Source:** Los Angeles Open Data Portal
- **Volume:** 843,000+ crime reports (~180 MB)
- **Focus:** Crime trends, demographics, geography, weapons, and temporal patterns

### Data Preparation

Prepared the dataset by:

- Cleaning missing and inconsistent values.
- Filtering invalid geographic coordinates.
- Standardizing categorical variables.
- Converting and validating date fields.
- Preparing reproducible analytical datasets.

### Feature Engineering

Created analytical variables including:

- Year
- Month
- Day of Week
- Victim demographics
- Crime categories
- Geographic coordinates
- Weapon classifications

These engineered features supported downstream statistical and geospatial analyses.

### Exploratory Data Analysis (EDA)

Conducted exploratory analyses to investigate:

- Annual crime trends.
- Monthly and weekly crime patterns.
- Crime type frequency.
- Victim demographics.
- Weapon involvement.
- Geographic crime distribution.

### Statistical Analysis

Applied statistical techniques to evaluate:

- Weekly crime fluctuations.
- Temporal crime trends.
- Regional crime differences.
- Pattern consistency across the study period.

### Geospatial Analytics

Developed interactive geographic visualizations using **Folium**, including:

- Crime density heatmaps.
- Spatial clustering.
- Geographic hotspot identification.
- Interactive map exploration.

### Data Visualization

Developed analytical visualizations using **Matplotlib**, **Plotly**, and **Seaborn**, including:

- Time-series charts.
- Distribution plots.
- Bar charts.
- Heatmaps.
- Interactive geographic visualizations.

# 📊 Analytical Insights

Analysis of over **843,000 Los Angeles crime reports** revealed several notable temporal, demographic, and geographic crime patterns.

### Temporal Crime Trends

- Crime activity declined during the initial COVID-19 pandemic period before increasing in subsequent years.
- Crime levels consistently peaked during the summer months.
- Friday and Saturday recorded the highest average crime volumes.
- Seasonal and weekly patterns remained relatively consistent throughout the study period.

### Geographic Distribution

- Crime was concentrated within major commercial and densely populated areas.
- Downtown Los Angeles, Hollywood, and South Los Angeles exhibited the highest crime densities.
- Interactive heatmaps highlighted persistent geographic hotspots across the city.

### Crime Characteristics

- Battery, burglary, and vandalism were among the most frequently reported offenses.
- Weapon involvement varied substantially across crime categories.
- Property and violent crimes displayed distinct temporal and spatial patterns.

### Victim Demographics

- Individuals between **20 and 50 years of age** represented the largest proportion of victims.
- Crime distributions differed across age groups and sex.
- Demographic analysis identified several population groups with consistently higher victimization rates.

### Statistical Findings

- Statistical testing supported significant variation in crime activity across days of the week.
- Geographic clustering indicated that crime was not randomly distributed throughout Los Angeles.
- Multiple analytical methods consistently identified the same high-risk regions and temporal patterns.

# ⚠️ Project Limitations

- Analysis is limited to publicly available LAPD crime data.
- Reported crimes may underrepresent actual crime occurrence.
- Missing demographic and geographic information required selective record exclusion.
- Findings represent historical patterns and should not be interpreted as predictive crime forecasts.

# 📈 Analytical Recommendations

Based on the analyses, several recommendations emerge:

- Prioritize resource allocation within persistent geographic crime hotspots.
- Increase law enforcement presence during peak weekend periods.
- Use demographic and geographic analyses to support targeted community outreach.
- Continuously monitor temporal crime trends to identify emerging patterns.
- Expand future analyses by incorporating socioeconomic, weather, and census data to improve explanatory insights.

# 🛠️ Technical Skills Demonstrated

### Programming

- Python

### Data Analysis

- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Hypothesis Testing
- Trend Analysis
- Temporal Analysis
- Demographic Analysis
- Geospatial Analysis
- Public Sector Analytics

### Data Preparation

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Missing Data Analysis
- Data Validation
- Large-Scale Dataset Processing

### Data Visualization

- Interactive Mapping
- Geospatial Heatmaps
- Time-Series Visualization
- Distribution Analysis
- Statistical Visualization
- Dashboard Development
- Data Storytelling

### Software

- Jupyter Notebook
- AWS S3

### Libraries

- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Folium
- SciPy

# 💡 What This Project Demonstrates

This project demonstrates the ability to design and execute an end-to-end Python data analytics workflow using a large real-world public dataset.

Key competencies demonstrated include:

- Cleaning and preparing large-scale datasets.
- Engineering analytical features from raw data.
- Conducting exploratory and statistical analyses.
- Developing geospatial analytical workflows.
- Creating interactive and publication-quality visualizations.
- Transforming complex datasets into actionable insights.
- Communicating analytical findings through reproducible data storytelling.

Although centered on Los Angeles crime data, the analytical workflow and technologies demonstrated are broadly transferable to business intelligence, data science, public sector analytics, finance, healthcare, operations, marketing, and other data-driven industries.

# 📁 Repository Structure

```text
Python-Data-Analysis-and-Geospatial-Crime-Analytics/
│
├── Datasets/
│   └── README.md
│       └── Download link to the original LAPD crime dataset
│
├── Outputs/
│   ├── Crimes in Los Angeles.ipynb
│   └── README.md
│
└── README.md
    └── Project documentation
```

**Datasets**

Contains a download link to the original Los Angeles Crime Data (2020–Present) dataset hosted on AWS S3.

**Outputs**

Contains the complete Jupyter Notebook implementing the full analytical workflow, including:

- Data cleaning and preprocessing
- Feature engineering
- Exploratory data analysis (EDA)
- Statistical analysis
- Geospatial analytics
- Interactive visualizations
- Analytical findings

# 🚀 Replicating the Project

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Folium
- SciPy

### Repository Setup

Clone the repository:

```bash
git clone https://github.com/yourusername/python-data-analysis-and-geospatial-crime-analytics.git
```

### Data Preparation

1. Download the Los Angeles Crime dataset from the **Datasets** directory.
2. Place the CSV file in your working directory.
3. Open `Outputs/Crimes in Los Angeles.ipynb`.

### Run the Analysis

Execute the notebook sequentially to perform:

- Data cleaning and preprocessing
- Feature engineering
- Exploratory data analysis (EDA)
- Statistical analysis
- Geospatial analysis
- Interactive visualization

### Review the Results

The notebook produces:

- Temporal trend analysis
- Crime type analysis
- Demographic analysis
- Statistical testing
- Interactive crime heatmaps
- Visual dashboards
- Analytical insights

# 📬 Contact Me

For questions or collaboration, feel free to reach out.

**Email**  
Awaleiabdi@outlook.com

**LinkedIn**  
https://www.linkedin.com/in/awale-abdi/
