# Formula 1 Tire Degradation Analysis

This project analyzes Formula 1 race data with a focus on tire degradation using FastF1 data. It includes pre-processed cache files, cleaned CSV datasets, and Jupyter notebooks for data exploration and visualization.

## Project Structure

- `Cache/` - Contains FastF1 cache data for multiple seasons and races, organized by year and Grand Prix.
- `f1_cleaned_tire_data.csv` - Cleaned tire data for analysis.
- `f1_degradation_by_compound_and_circuit.csv` - Tire degradation data grouped by compound and circuit.
- `f1_tire_degradation_data.csv` - Raw or processed tire degradation data.
- `TireDegradation.ipynb` - Jupyter notebook for tire degradation analysis and visualization.

## Setup

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd <repo-directory>
   ```
2. **Install dependencies**
   Ensure you have Python 3.8+ and install required packages:
   ```bash
   pip install fastf1 pandas numpy matplotlib jupyter
   ```
3. **(Optional) Set up FastF1 cache**
   The `Cache/` directory already contains pre-fetched data. To fetch new data, configure FastF1 as needed in your scripts or notebooks.

## Usage

- Open `TireDegradation.ipynb` in Jupyter Notebook or JupyterLab:
  ```bash
  jupyter notebook TireDegradation.ipynb
  ```
- Explore and run the cells to analyze tire degradation trends, visualize data, and generate insights.

## Data Sources

- [FastF1](https://theoehrly.github.io/Fast-F1/) for session and timing data.
- CSV files in the root directory for cleaned and aggregated datasets.

## Contributing

Feel free to open issues or submit pull requests for improvements, bug fixes, or new features.
