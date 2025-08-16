# Data Directory

This directory contains all datasets used in the data science projects.

## Structure

- **`raw/`**: Original, unprocessed datasets
- **`processed/`**: Cleaned and preprocessed datasets ready for analysis

## Datasets

### Raw Data
Place original CSV, Excel, JSON, or other data files here before any processing.

### Processed Data
Place cleaned and transformed datasets here after preprocessing steps.

## Data Sources

- **Healthcare Data**: Medical datasets for disease prediction
- **Business Data**: Sales, customer, and financial datasets
- **Public Datasets**: Open-source datasets for analysis and visualization

## Usage

When working with notebooks, reference data files using relative paths:
```python
# For raw data
df = pd.read_csv('../data/raw/dataset.csv')

# For processed data
df = pd.read_csv('../data/processed/cleaned_dataset.csv')
```

## Data Privacy

- Ensure no sensitive or personal information is included in datasets
- Use anonymized or synthetic data when necessary
- Follow data privacy best practices and regulations
