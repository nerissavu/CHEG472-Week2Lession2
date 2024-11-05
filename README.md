# Biomass Gasification Dataset\n
\n
## Dataset Description\n
- 244 samples\n
- 25 features\n
- Focus on gasification product analysis\n
\n
## Features\n
- Feed compositions (C, H, N, S, O, ASH)\n
- Process parameters (Temp: 80-400°C, Time, BC)\n
- Chemical bonds (C-H, C=O, etc.)\n
- 24 different feed types (fruit waste, industrial waste, etc.)\n
\n
## Target Variables\n
- CO2 mole fraction\n
- H2 mole fraction\n
- Hydrogen selectivity\n
- CO mole fraction\n
- CH4 mole fraction\n
\n
## Processing Steps\n
1. Data cleaning (removed 7 outliers)\n
2. Feature engineering (C/H, O/H ratios)\n
3. One-hot encoding of feed types\n
4. Split into X (features) and Y (targets)\n
\n
## File Structure\n
- `features.csv`: Input variables\n
- `targets.csv`: Output gas compositions\n
\n
## Usage\n
```python\n
import pandas as pd\n
df = pd.read_excel('Biomass Gasification Dataset.xlsx')\n
```\n
