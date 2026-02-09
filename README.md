# ML Classification and Clustering Project

This project analyzes World Bank gender-related data using machine learning classification, clustering, and regression techniques.

## How to Run

### Prerequisites

1. Install Python 3.8 or higher
2. Install required dependencies:

```bash
pip install -r requirements.txt
```

### Running the Notebooks

1. Navigate to the project directory:
```bash
cd proj1
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open and run the notebooks in order:
   - `part1-1.ipynb` → EDA + Classification
   - `part1-2.ipynb` → Feature Extraction
   - `part2-1.ipynb` → EDA + Clustering
   - `part2-2.ipynb` → Regression

---

## File Descriptions

### Notebooks

| File | Description |
|------|-------------|
| **part1-1.ipynb** | **EDA + Classification: Gender Ratio Class Prediction** <br> • Part 1.0: Exploratory Data Analysis <br> • Part 1.1: Classification with 3 workflows: <br> &nbsp;&nbsp;- Workflow 1: Decision Tree + Correlation Filter + Forward Selection <br> &nbsp;&nbsp;- Workflow 2: KNN + One-Hot Encoding + Correlation Filter <br> &nbsp;&nbsp;- Workflow 3: Random Forest + RFE <br> • Feature importance analysis <br> • ANOVA and Chi-square tests for Region vs Gender Ratio Class |
| **part1-2.ipynb** | **Feature Extraction** <br> • PCA (Principal Component Analysis) with component analysis <br> • LDA (Linear Discriminant Analysis) with component analysis |
| **part2-1.ipynb** | **EDA + Clustering: Country Grouping** <br> • Part 2.0: Exploratory Data Analysis <br> • Part 2.1: K-Means Clustering <br> • Clustering interpretation graphs: Radar chart, PCA plot, Box plot |
| **part2-2.ipynb** | **Regression: GNI Per Capita Prediction** <br> • Part 2.2: Regression with 2 workflows: <br> &nbsp;&nbsp;- Workflow 1: Correlation Filter + Linear Regression <br> &nbsp;&nbsp;- Workflow 2: RFE + Random Forest <br> • Feature importance analysis |

### Data Files

| File | Description |
|------|-------------|
| **data/worldbank_2017_2021.csv** | World Bank dataset covering years 2017-2021 with various socioeconomic indicators |
| **data/worldbank_gender_2021.csv** | World Bank gender-specific indicators for 2021 |
| **data/countries_regions.xlsx** | Country-region mapping for geographical grouping |

### Reports

| File | Description |
|------|-------------|
| **report.pdf** | Final project report with analysis results and conclusions |

---

## Project Structure

```
proj1/
├── README.md                           # This file
├── requirements.txt                    # Python dependencies
├── part1-1.ipynb                       # EDA + Classification
├── part1-2.ipynb                       # Feature Extraction (PCA, LDA)
├── part2-1.ipynb                       # EDA + Clustering
├── part2-2.ipynb                       # Regression
├── report.pdf                          # Project report
└── data/
    ├── worldbank_2017_2021.csv         # Main dataset (2017-2021)
    ├── worldbank_gender_2021.csv       # Gender indicators (2021)
    └── countries_regions.xlsx          # Country-region mapping
```
