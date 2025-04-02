# Diamond Analysis Project

This project involves data exploration and analysis of diamond characteristics using both Excel and CSV files. The goal is to extract insights about pricing, quality, and features of diamonds, and to identify the top 5 most valuable ones.

## Project Structure

```bash
diamond-analysis-project/
├── notebooks/
│   └── diamond_analysis.ipynb              # Main analysis notebook
├── data/
│   ├── data.xlsx                           # Raw dataset
│   ├── diamond_analysis_report.xlsx        # Processed or summarized Excel report
│   └── top_5_diamonds.csv                  # Final top 5 diamonds data
├── README.md                               # Project documentation
├── requirements.txt                        # Dependencies
└── .gitignore                              # Files to exclude from Git
```

## 📊 Description

The dataset includes multiple features of diamonds, such as:
- Carat
- Cut
- Color
- Clarity
- Price
- Depth
- Table
- Dimensions

## 🔍 Goals

- Clean and explore the data
- Visualize relationships between features and price
- Identify patterns that impact diamond valuation
- Find the top 5 most expensive diamonds

## ✅ Output

A final CSV file with the top 5 diamonds by value, and a structured notebook showing all analysis steps.

## ⚙️ Setup

```bash
pip install -r requirements.txt
jupyter notebook notebooks/diamond_analysis.ipynb
```

Author
Zarina Sakhipova