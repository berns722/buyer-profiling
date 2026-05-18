# Austo Automobile — Buyer Profile Analysis

A data analysis project identifying distinct buyer profiles across three car segments 
for Austo, a UK-based automobile company expanding into the US market.

## Key Findings

- **Age is the strongest segmentation signal** — a clear Age → Make → Price progression 
exists across all three segments.
- **Hatchback buyers** are the youngest (~26), predominantly male, with the lowest 
salaries (~$55k) and household income (~$72.6k). Average car price: $25,500.
- **Sedan buyers** are middle-aged (~36), gender-balanced, primarily salaried, with 
mid-range salaries (~$62k) and household income (~$82k). Average car price: $42,600.
- **SUV buyers** are the oldest (~47), gender-balanced, highest earners (~$72k salary, 
~$99k household income), with greater financial stability. Average car price: $59,300.
- All three segments are predominantly married with post-graduate degrees.

## Recommendations

- Target younger demographics (22-30) with affordable Hatchbacks emphasizing 
practicality and financing options.
- Target mid-career professionals (28-45) with Sedans emphasizing comfort and 
professional image.
- Target older, affluent buyers (35-60) with SUVs emphasizing luxury, safety, 
and premium features.

## Project Structure

```
buyer-profiling/
├── data/
│   └── austo_automobile.csv
├── notebooks/
│   └── analysis.ipynb
├── src/
│   └── eda.py
└── README.md
```
## How to Run

1. Clone the repository:
```bash
   git clone https://github.com/berns722/buyer-profiling.git
   cd buyer-profiling
```

2. Create and activate the conda environment:
```bash
   conda env create -f environment.yml
   conda activate buyer-profiling
```

3. Launch the notebook:
```bash
   jupyter notebook notebooks/analysis.ipynb
```

## Methodology

Pure exploratory data analysis — no predictive modeling. Analysis covers univariate 
distributions, multivariate relationships, and segment-level profiling using 
1,581 buyer records across 14 features.

## Tools

Python, Pandas, Matplotlib, Seaborn 

## Further Direction

- **Dynamic dashboard** — buyer profiles and segment distributions could feed a 
Power BI or Streamlit dashboard for interactive exploration.
- **Predictive modeling** — profiles could serve as a foundation for a classification 
model predicting car segment preference from buyer demographics.