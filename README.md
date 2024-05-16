README

Forest Coverage in India Analysis

This project analyzes the forest coverage in India for the years 2019 and 2023 using data visualization techniques. It combines forest coverage data with geographical boundaries to create visual representations and comparisons.

Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries: `openpyxl`, `pandas`, `geopandas`, `matplotlib`, `seaborn`, `plotly`

Installation

Install the required libraries using pip:
```bash
pip install openpyxl geopandas plotly
```

Usage

1. Clone the Repository: Download or clone the repository to your local machine.

2. Upload Data: Ensure the following files are in the working directory:
   - `Forest_2019.xlsx`
   - `Forest_2023.xlsx`
   - `Indian_states.shp` (along with associated files like `.dbf`, `.shx`, etc.)

3. Run the Notebook: Open and run the Jupyter Notebook `forest-coverage-india-geopandas.ipynb` to generate the visualizations.

Data Sources

- Forest_2019.xlsx: Contains forest coverage data for 2019.
- Forest_2023.xlsx: Contains forest coverage data for 2023.
- Indian_states.shp: Shapefile with geographical boundaries of Indian states.

Visualizations

The notebook produces the following visualizations:

1. Choropleth Maps: Display the percentage of geographical area covered by forests for each state/UT in 2019 and 2023.
2. Bar Plots: Compare the forest coverage percentages across states/UTs for the years 2019 and 2023.

Conclusion

This project provides a comprehensive visual analysis of the changes in forest coverage across Indian states/UTs between 2019 and 2023. The visualizations help in understanding the geographical distribution and temporal changes in forest coverage, contributing to environmental and conservation efforts.

Future Work

Further enhancements could include:

- Incorporating data from more years to analyze trends over a longer period.
- Adding more detailed forest classification data.
- Integrating additional geographical data layers for a more in-depth analysis.
