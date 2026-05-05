# Battery Data Analysis

This project analyzes lithium-ion battery data to understand its performance, usage patterns, and data quality.

## Objective
The goal is to clean the dataset and extract useful insights related to:
- Data availability
- Charging and discharging cycles
- Battery efficiency
- Idle behavior

## Project Structure

```
Battery Analysis/
│
├── data/
│   ├── battery_data_logs.csv
│   ├── data_code_details.csv
│
├── output/
│   ├── cleaned_dataset.csv
│   ├── analysis_dataset.csv
│   ├── daily_count.csv
│   ├── daily_energy.csv
│
├── notebook/
│   ├── battery_analysis.ipynb
│
├── README.md
├── .gitignore
```

## Key Analysis Performed
- Daily data availability check
- Cycle detection (charging & discharging)
- Cycle duration analysis
- Energy throughput calculation
- Idle time analysis
- Day-wise efficiency analysis
- Peak charging day detection
- Usage classification

## Key Findings
- Some days have missing or extra data
- Battery is idle for a significant portion of time
- Charging time is generally higher than discharging time
- Efficiency varies over time
- Some abnormal cycles were detected

## Summary of Insights
- Data is not perfect for every day. Some days have missing records, and some days have extra data.
- The battery stays idle for a large amount of time, which means it is not always in use.
- Charging usually takes more time compared to discharging.
- Battery efficiency is not constant. It changes over different days.
- Some cycles take unusually long time, which may indicate missing data or abnormal behavior.
- There are certain days where charging is very high, showing heavy battery usage.
- Based on availability and efficiency, days can be classified into low data, normal usage, and good usage.
- Overall, the analysis shows how the battery is used, how efficient it is, and where problems may exist in the data.

## Deliverables
- Cleaned dataset (CSV)
- Processed dataset for analysis
- Jupyter Notebook with full analysis
- Visualizations (graphs)
- Summary of insights

## Tools Used
- Python (Pandas, NumPy, Matplotlib)

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Open the notebook from the `notebook/` folder
3. Run all cells step by step
4. Ensure data files are placed inside the `data/` folder