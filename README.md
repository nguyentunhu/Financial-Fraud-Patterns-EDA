# Financial Fraud Detection EDA

A comprehensive exploratory data analysis of synthetic financial transaction data to identify patterns and characteristics of fraudulent activities.

## 📊 Project Overview

This project analyzes a synthetic financial dataset containing 636,620 transactions to understand fraud patterns and improve detection capabilities. The analysis focuses on transaction types, amounts, timing, and balance changes to reveal key insights about fraudulent behavior.

## 🗂️ Dataset Information

- **Total Transactions**: 636,620
- **Features**: 11 columns
- **Target Variable**: `isFlagged` (fraud indicator)
- **Transaction Types**: CASH_OUT, PAYMENT, CASH_IN, TRANSFER, DEBIT
- **Time Range**: Sequential steps (1-743)

### Dataset Schema
```
- step: Transaction sequence number
- type: Transaction type (CASH_OUT, PAYMENT, CASH_IN, TRANSFER, DEBIT)
- amount: Transaction amount
- nameOrig: Origin account identifier
- oldbalanceOrg: Origin account balance before transaction
- newbalanceOrig: Origin account balance after transaction
- nameDest: Destination account identifier
- oldbalanceDest: Destination account balance before transaction
- newbalanceDest: Destination account balance after transaction
- isFraud: Actual fraud label (ground truth)
- isFlagged: Fraud detection system flag
```

## 🔧 Technical Requirements

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

### Required Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
from plotly.subplots import make_subplots
```

## 📈 Analysis Components

### Data Overview and Quality Assessment
- Dataset shape and structure analysis
- Missing values detection
- Data type validation
- Sample data exploration

### Fraud Detection Performance Analysis
- Confusion matrix visualization
- Detection accuracy metrics
- False positive/negative analysis

### Transaction Type Distribution Analysis
- Overall transaction type breakdown
- Fraud-specific transaction patterns
- Comparative analysis between legitimate and fraudulent transactions

###  Amount Distribution Analysis
- Fraud transaction amount patterns
- Density plot analysis
- Statistical summary of transaction amounts

### Customer vs Merchant Analysis
- Target profile identification
- Fraud distribution by account type

### Temporal Pattern Analysis
- Transaction timing patterns
- Steps between valid and fraudulent transactions
- Fraud timing strategies

### Balance Change Analysis
- Origin vs destination balance changes
- Transaction amount vs balance change correlation
- Fraud detection through balance verification

## 📊 Visualization Gallery

### Generated Visualizations:
1. **Confusion Matrix Heatmap** - Fraud detection performance
2. **Transaction Type Donut Charts** - Overall vs fraud-specific distributions
3. **Amount Density Plot** - Fraud transaction amount patterns
4. **Balance Change Scatter Plot** - Amount vs balance relationship with fraud indicators
5. **Customer vs Merchant Bar Chart** - Target analysis
6. **Temporal Analysis Histograms** - Timing pattern exploration

### Custom Styling:
- Fraud-intuitive color palette 
- Professional formatting with clear labels
- Interactive elements where applicable

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements. Areas for enhancement:
- Advanced statistical testing
- Machine learning model implementation
- Interactive dashboard development
- Additional fraud detection algorithms

*This analysis demonstrates comprehensive EDA capabilities for fraud detection in financial datasets, showcasing both technical proficiency and business acumen in data analysis.*
