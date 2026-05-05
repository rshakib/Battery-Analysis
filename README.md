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