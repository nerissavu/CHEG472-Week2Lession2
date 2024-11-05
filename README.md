# Biomass Gasification Dataset

## Dataset Description
- 244 samples
- 25 features
- Focus on gasification product analysis

## Features
- Feed compositions (C, H, N, S, O, ASH)
- Process parameters (Temp: 80-400°C, Time, BC)
- Chemical bonds (C-H, C=O, etc.)
- 24 different feed types (fruit waste, industrial waste, etc.)

## Target Variables
- CO2 mole fraction
- H2 mole fraction
- Hydrogen selectivity
- CO mole fraction
- CH4 mole fraction

## Processing Steps
1. Data cleaning (removed 7 outliers)
2. Feature engineering (C/H, O/H ratios)
3. One-hot encoding of feed types
4. Split into X (features) and Y (targets)

## File Structure
- `features.csv`: Input variables
- `targets.csv`: Output gas compositions

## Usage
```python
import pandas as pd
df = pd.read_excel('Biomass Gasification Dataset.xlsx')
```
