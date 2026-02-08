This project analyzes World Bank gender-related data using machine learning
classification and regression techniques.


part1-1.ipynb - Classification: Gender Ratio Class Prediction
  - Part 1.0: EDA for part1
  - Part 1.1: Classification
    Implements 3 classification workflows:
      Workflow 1: Decision Tree + Correlation Filter + Forward Selection
      Workflow 2: KNN + One-Hot Encoding + Correlation Filter
      Workflow 3: Random Forest + RFE 
    Model interpretation with feature importance analysis
    ANOVA and Chi-square tests for Region vs Gender Ratio Class

part1-2.ipynb - Feature Extraction
  - Part 1.2: Feature Extraction
    PCA with component analysis
    LDA with component analysis

part2-1.ipynb - Clustering: Country Grouping
  - Part2.0:EDA
  - Part 2.1: Clustering
    Implements clustering workflows:
      K-Means
    Clustering interpretation graph
      Radar chart
      PCA plot
      Box plot
part2-2.ipynb - Regression: GNI Per Capita Prediction
  Part 2.2: Regression
    Implements 2 progressive regression workflows:
      Workflow 1: Correlation Filter + Linear Regression
      Workflow 2: RFE + Random Forest
    Model interpretation with feature importance analysis


