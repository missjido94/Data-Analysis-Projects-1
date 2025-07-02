# 🔋 Transpower Energy Generation Analysis

## Project Overview
This analysis examines New Zealand's upcoming electricity generation projects to understand the evolving energy landscape. The study focuses on generation technology distribution, capacity planning, and grid connection requirements to support Transpower's strategic decision-making.

## Key Questions
- What generation technologies are dominating future energy projects?
- How is capacity distributed across different generation types?
- What voltage levels are required for different project scales?
- How does this align with New Zealand's renewable energy goals?

## Data Source
- **Dataset:** Transpower upcoming generation projects
- **Size:** 132 rows, 85 distinct project records
- **Variables:** Generation Type, Maximum Capacity (Max MW), Connection Voltage
- **Data Quality:** 7 missing values in Connection Voltage column

## Key Findings

### 1. Renewable Energy Dominance
- **Solar leads:** 34.5% of all upcoming projects
- **Solar + Battery Storage:** 31% of projects
- **Wind:** 21.8% of projects
- **Clear trend:** Strong shift toward renewable and storable energy

### 2. Capacity Distribution
- Solar and Solar + BESS projects contribute the most to total planned capacity
- Connection voltages range from 11 kV to 220 kV
- **Voltage Categories:**
  - 11-66 kV: Low voltage for rural/local generation
  - 110 kV: Medium voltage for regional projects
  - 220 kV: High voltage for large-scale generation

### 3. Voltage-Capacity Relationship
- **Average Connection Voltage:** 144.27 kV
- **Range:** 11.0 kV - 220.0 kV
- **Key Insight:** Positive correlation between voltage and capacity, but high voltage doesn't always mean high capacity

## Visualizations
![Generation Type Distribution](./visualizations/generation_distribution.png)
*Distribution of generation technologies showing solar's dominance*

![Capacity vs Voltage Analysis](./visualizations/capacity_voltage_plot.png)
*Relationship between maximum capacity and connection voltage*

## Strategic Implications
1. **Infrastructure Planning:** Current grid must support increasing high-voltage renewable connections
2. **Investment Focus:** Solar + battery storage represents the future of flexible energy supply
3. **Technology Shift:** Moving away from traditional hydro due to site constraints
4. **Grid Resilience:** Battery storage integration critical for reliable renewable supply

## Tools Used
- **Development Environment:** Spyder IDE
- **Libraries:** Python (Pandas, Matplotlib, Seaborn, NumPy)
- **Notebooks:** Jupyter for documentation and reproducible analysis
- **Analysis:** Data cleaning, statistical analysis, and visualization

## How to Run This Analysis
1. Install requirements: `pip install -r requirements.txt`
2. Open notebook: `notebooks/energy_analysis.ipynb`
3. Run all cells to reproduce analysis

## Files Structure
- `data/raw/` - Original Transpower dataset
- `data/processed/` - Cleaned and prepared data
- `notebooks/` - Complete analysis workflow
- `visualizations/` - All charts and graphs
- `requirements.txt` - Python dependencies

## Recommendations
- **Immediate:** Review grid infrastructure capacity for high-voltage renewable connections
- **Strategic:** Prioritize investment in solar + battery storage technologies
- **Planning:** Factor renewable energy dominance into long-term grid development
- **Further Analysis:** Investigate site availability and stakeholder consultation requirements

