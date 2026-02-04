# King County Housing Data Analysis - EDA Project

## Project Overview
This project explores housing sales data from King County, Washington, using exploratory data analysis (EDA) techniques. The goal is to identify key factors that influence home prices and translate these insights into actionable recommendations for a client.

## Client
**Amy Williams (Seller)**  
Amy owns multiple properties and aims to sell high-value homes in prime locations while also selling average-priced homes in outskirt areas over time.

## Repository Structure
```
├── EDA.ipynb              # Main analysis notebook
├── data/                  # Data folder (CSV files)
├── assignment.md          # Project assignment details
├── column_names.md        # Data dictionary
├── workflow.md            # EDA methodology guide
├── requirements.txt       # Python dependencies
└── README.md             # This file
```

## Setup Instructions

### Prerequisites
- Python 3.11.3
- pip

### Installation

1. Clone this repository
```bash
git clone <your-repo-url>
cd eda-project
```

2. Create and activate virtual environment
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

4. Launch Jupyter
```bash
jupyter lab
```

5. Open `EDA.ipynb` and run the analysis

## Data Source
The analysis uses the King County Housing dataset from the `eda` schema of the bootcamp database. The data includes:
- Home sale prices
- Property characteristics (bedrooms, bathrooms, square footage)
- Location data (ZIP codes, coordinates)
- Building quality metrics

See `column_names.md` for detailed descriptions of all columns.

## Key Findings

### Insights
1. **Living area is the strongest price driver** - Square footage has the highest correlation with home prices
2. **Bedroom count shows diminishing returns** - Beyond 4 bedrooms, additional rooms don't significantly increase value
3. **Location matters significantly** - Prime ZIP codes command substantially higher prices than outskirt areas

### Recommendations
1. **Prioritize prime locations for quick sales** - Focus on selling properties in high-value ZIP codes to maximize returns
2. **Invest in living space improvements** - Renovations that increase square footage provide better ROI than adding bedrooms
3. **Use outskirt properties strategically** - Gradual sales of average-priced homes generate steady income while maintaining a low profile

## Methodology
- Exploratory Data Analysis (EDA)
- Statistical correlation analysis
- Geographical analysis by ZIP code
- Data visualization and pattern identification
- Hypothesis testing

## Technologies Used
- Python 3.11
- Pandas & NumPy (data manipulation)
- Matplotlib & Seaborn (visualization)
- Altair (interactive visualizations)
- Jupyter Lab (development environment)

## Author
Sarra - Spiced Academy Data Science Bootcamp

## License
See LICENSE file for details
