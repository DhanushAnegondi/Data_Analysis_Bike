```markdown
# London Bike Rides Analysis

This repository contains an analysis of London Bike Rides data, focusing on the relationship between ride counts, temperature, and wind speed. The analysis includes a Tableau dashboard that visualizes key metrics and trends over the specified period.

## Dashboard Overview

![Tableau Dashboard](/Users/dhanushchandra/Downloads/London_Bike_project/Tableau Dashboard 1.png)

### Key Metrics and Visualizations

- **Total Rides:** The total number of bike rides recorded between March 21, 2015, and February 1, 2016, is 8,787,723.
- **50-Day Moving Average:** A moving average of bike rides over a 50-day period, highlighting trends and seasonality in the data.
- **Temperature and Wind Speed Analysis:** A detailed table showing the number of rides corresponding to different temperature and wind speed ranges, providing insights into how weather conditions affect bike usage.

## Project Structure

- `data/`: Contains the raw and processed data used for analysis.
- `notebooks/`: Jupyter notebooks with data cleaning, analysis, and visualization code.
- `dashboard/`: Tableau workbook files and related assets.
- `scripts/`: Python scripts for data preprocessing and analysis.

## Getting Started

### Prerequisites

- [Python 3.x](https://www.python.org/)
- [Tableau Desktop](https://www.tableau.com/products/desktop)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Jupyter Notebook](https://jupyter.org/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mochen862/LondonBikeRides.git
   cd LondonBikeRides
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter notebooks in the `notebooks/` directory to explore the data analysis and visualization steps.
2. Load the Tableau workbook files in the `dashboard/` directory to view and interact with the dashboard.

## Data Sources

The data used in this project was sourced from [insert data source link if available].

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push to your branch.
5. Create a pull request.

