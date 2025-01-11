# Revenue Forecasting and Sales Analytics for ProcDNA

## Project Overview
This project analyzes sales and market data for ProcDNA using five provided CSV files. The tasks involve revenue forecasting, calculating sales representatives' costs, market coverage analysis, and workload index evaluation. All tasks are completed using the Python `pandas` library for data manipulation and visualization.

---

## Repository Structure

```
root
|-- data/                     # Directory for the input CSV files
|-- notebooks/                # Jupyter notebooks used for analysis (if applicable)
|-- scripts/                  # Python scripts for data processing and analysis
|-- output/                   # Generated reports and visualizations
|-- README.md                 # Project documentation (this file)
|-- requirements.txt          # Python dependencies
```

---

## Files Description
- `data/`: Contains the input CSV files provided.
- `notebooks/` or `scripts/`: Contains the implementation of the analysis tasks.
- `output/`: Stores visualizations, final reports, or exported CSV results.

---

## Python Libraries
This project uses the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Run `pip install -r requirements.txt` to install all dependencies.

---

## Problem Statements and Solutions

### 1. Data Quality Checks
**Solution**: Performed the following data checks on all datasets:
- Missing values detection.
- Data type validation.
- Duplicate records identification.
- Range and consistency checks for numerical values.

### 2. Revenue Forecast for 2024
**Tasks**:
- Calculate ProcDNA's revenue forecast using data from Table 1.1.
- Compute Total TRx and $/TRx for both products.
- Segment HCPs into deciles based on their total market dollar potential.
- Visualize key insights from the segmentation.

**Solution**: Pandas operations and visualizations (using `matplotlib` and `seaborn`).

### 3. Cost Per Call and Sales Representatives Hiring
**Tasks**:
- Calculate the cost per call for outreach sales reps, assuming $250,000 per representative.
- Determine how many sales reps are needed to cover at least 50% of Market TRx.
- Incorporate the hiring budget constraint of 90 reps.

**Solution**: Applied filtering, cost computation, and aggregation.

### 4. Return on Investment (ROI)
**Tasks**:
- Evaluate ROI for hiring sales reps.
- Analyze ROI impact for hiring 110 reps instead of 90.

**Solution**: Computed ROI and compared different scenarios.

### 5. Loyalty Program Tier Classification
**Task**: Classify accounts into tiers based on prescription percentages.

**Solution**: Calculated tier qualifications and applied corresponding discounts.

### 6. Workload Index Calculation
**Task**: Compute workload index for all territories.

**Solution**: Followed the steps provided from row 30 onward using pandas operations.

### 7. Balanced Workload Index
**Task**: Count territories within and outside the balanced workload index range (800-1,200).

**Solution**: Conditional filtering and counting.

### 8. Workload Index Visualization
**Task**: Plot workload index for all territories and regions in descending order.

**Solution**: Visualized the workload distribution using `matplotlib`.

### 9. Presentation Slides
**Task**: Summarized key findings and visualizations into slides.

**Solution**: Created a professional presentation highlighting results and insights.

---

## Usage Instructions
1. Place the input files in the `data/` directory.
2. Run the scripts in `scripts/` or notebooks in `notebooks/` to execute the analysis.
3. Generated outputs are stored in the `output/` directory.

---

## Key Insights
- Segmenting HCPs into deciles provides targeted sales strategies.
- ROI analysis helps in optimizing the hiring budget.
- Workload index evaluation improves territory management efficiency.

---

## Contributions
Contributions, issues, and suggestions are welcome. Please create a pull request or issue for any improvements.

---

Refer the doc link and ppt link for outputs
PPT:
https://drive.google.com/file/d/1izFkfE_0LZ2O8nvlIPXYd9Djzo4t335K/view?usp=sharing

DOCX:
https://docs.google.com/document/d/1zsmvmi6a2QbOU_4QD3V6I-paI0Z7Uef0/edithttps://docs.google.com/document/d/1zsmvmi6a2QbOU_4QD3V6I-paI0Z7Uef0/edit

