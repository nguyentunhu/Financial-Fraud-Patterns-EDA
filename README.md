# Synthetic-Financial-Dataset-EDA
The **Synthetic Financial Dataset EDA** project is a comprehensive exploratory data analysis (EDA) of a synthetic financial dataset. This project aims to uncover insights and patterns within the dataset, focusing on various aspects of financial transactions, including fraud detection.

### Dataset used: [Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)
PaySim first paper of the simulator:

E. A. Lopez-Rojas , A. Elmir, and S. Axelsson. "PaySim: A financial mobile money simulator for fraud detection". In: The 28th European Modeling and Simulation Symposium-EMSS, Larnaca, Cyprus. 2016

### Key Features:
- **Data Collection**: The dataset is sourced from Kaggle and includes detailed financial transaction records.
- **Data Cleaning**: The data is meticulously cleaned to ensure accuracy, including handling missing values, data type conversions, and removing duplicates.
- **Univariate Analysis**: 
  - Count of transactions by type to understand the distribution and identify the most common transaction types.
  - Count of fraud transactions to assess the prevalence of fraud in the dataset.
  - Count of transactions flagged as fraud to evaluate the effectiveness of the fraud detection mechanism.
- **Multivariate Analysis**: 
  - Correlation analysis to examine relationships between multiple numerical variables and identify patterns and trends.
- **Bivariate Analysis**: 
  - Analysis of transaction amounts by type, step (hour), and day to observe trends and fluctuations.
  - Confusion matrix for fraud detection to evaluate the performance of the fraud detection model.

### Visualizations:
- Various plots, including scatter plots, line plots, bar plots, and heatmaps, are used to visualize the data and uncover insights.

### Tools and Libraries:
- **Python**: The primary programming language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning and model evaluation.
