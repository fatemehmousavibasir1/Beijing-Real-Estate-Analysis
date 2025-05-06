
#  Beijing Real Estate Data Analysis

This project presents a comprehensive analysis of real-world housing data from **Beijing**, focusing on extracting insights through data preprocessing, feature engineering, and visualizations. The project is structured into **five key stages**, each addressing a specific aspect of data preparation and analysis.

##  Project Overview

The dataset contains detailed information about property transactions in Beijing. The goal is to clean, enrich, and visualize the data to uncover meaningful patterns about the housing market.

---

##  Project Structure

The analysis is carried out through five main notebooks, each representing a distinct phase of the data workflow:

### 1. **Data Cleaning and Initial Preparation**
- Load the dataset and inspect its structure.
- Remove irrelevant columns.
- Handle missing values appropriately.

### 2. **Data Formatting and Outlier Removal**
- Convert features into proper data types.
- Detect and remove outliers to improve data quality.

### 3. **Feature Engineering**
- Derive new useful features from existing ones.
- Prepare enriched data for advanced analysis and visualization.

### 4. **Geospatial Visualization**
- Use latitude and longitude data to map properties.
- Identify patterns in housing distribution across Beijing.

### 5. **Temporal Analysis**
- Analyze trends based on transaction dates.
- Understand how market behavior changes over time.

---

##  Dependencies

This project uses the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

Install them using:

```bash
pip install numpy pandas matplotlib seaborn
```

---

##  Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/fatemehmousavibasir1/beijing-housing-analysis.git
   ```

2. Start from `Beijing_1_fill_missing_values.ipynb` and run each notebook in sequence.
---

##  File Structure

```
.
├── Beijing_1_fill_missing_values.ipynb
├── Beijing_2_correct_format_and_outliers.ipynb
├── Beijing_3_add_new_features.ipynb
├── Beijing_4_show_on_map.ipynb
├── Beijing_5_time_series.ipynb
├── README.md
└── data/
    └── housing_data.csv
`
