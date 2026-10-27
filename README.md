# Indian_Criminal_Law_Dataset
An Indian Criminal Law Dataset based on the Bharatiya Nyaya Sanhita (BNS), 2023, containing 5,000 records covering 476 sections. Includes offence descriptions, BNS section numbers, punishment information, legal classifications, and section-wise references for research, data analysis, and educational purposes.
# Indian Criminal Law Dataset (BNS 2023)

## Overview
The Indian Criminal Law Dataset is a structured collection of legal information based on the Bharatiya Nyaya Sanhita (BNS), 2023. It provides information about criminal offences, legal provisions, punishments, and related classifications.

## Dataset Information
- **Total Records:** 5,000
- **Sections Covered:** 476
- **File Format:** Excel (.xlsx)
- **Worksheets:** README, Dataset, Section_Master

## Dataset Features
- BNS section numbers and offence names
- Descriptions of offences and legal provisions
- Punishment information
- Legal classifications, including cognizable and bailable status
- Section-wise information for easier reference

## Objectives
- Organize Indian criminal law information in a structured format.
- Support educational activities and legal research.
- Enable data analysis and visualization.
- Provide a dataset for experimenting with AI, machine learning, and natural language processing applications.

## Tools and Technologies
- Microsoft Excel
- Python
- Pandas
- Jupyter Notebook

## Usage
Download the Excel file and open it using Microsoft Excel. For programmatic analysis, load the workbook using Python and Pandas.

```python
import pandas as pd

df = pd.read_excel(
    "Indian_Criminal_Law_Dataset.csv.xlsx",
    sheet_name="Dataset"
)

print(df.head())
```

## Applications
This dataset can be used for legal information retrieval, text classification, data visualization, academic projects, and AI-based legal information systems.

## Disclaimer
This dataset is intended for educational and research purposes only. Legal information should be verified against authoritative government sources before being used for legal decisions.
