# Data601

## Project Overview
This project analyzes a dataset of property energy consumption and greenhouse gas (GHG) emissions to identify key trends, seasonal variations, and opportunities for improving energy efficiency.

## Dataset
The dataset contains information on property types, energy usage, GHG emissions, and building characteristics. Key variables include:
- `Property GFA - Self-Reported (m²)`
- `Total GHG Emissions (Metric Tons CO2e)`
- `Site EUI (GJ/m²)`
- `Electricity Use - Grid Purchase (kWh)`
- `Site Energy Use (GJ)`
## Methodology
1. **Data Cleaning**:
   - Handled missing values by dropping columns with >40% missing data and filling numerical/categorical columns with median/mode.
   - Used regex to:
     - Extract numeric values from text-based columns.
     - Standardize postal codes to the Canadian format (A1A 1A1).
     - Clean property names and addresses.
2. **Exploratory Data Analysis **:
   - Generated summary statistics and identified outliers.
   - Computed average Energy Use Intensity (EUI) by property type and total GHG emissions by year.
3. **Visualization**:
   - Created line charts, bar charts, and heatmaps to visualize trends and variations.

## Challenges Faced
- Handling inconsistent data formats in text-based columns.
- Identifying and correcting outliers in GHG emissions.
- Standardizing postal codes using regex.

## Insights Gained
- Average Site EUI has declined over the years, indicating improved energy efficiency.
- Heated swimming pools and older office buildings have the highest energy consumption.
- Seasonal variations show higher energy usage during colder months.
