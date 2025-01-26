# EXPLORER-ACCELERATOR---Transportation-Data-Science-Project
This project analyzes motor vehicle crash data to identify patterns in accidents across time and locations. It uses time series and geospatial analysis, including heatmaps and severity mapping, to offer insights into road safety and help prioritize interventions in high-risk areas.

# Motor Vehicle Crash Analysis for Road Safety

## Project Description
This project analyzes motor vehicle crash data to derive insights and make recommendations to improve road safety. Through data exploration, time series analysis, and geospatial visualization, the project uncovers patterns in crash occurrences based on time, location, and severity. The goal is to provide actionable insights that can help transportation authorities prioritize areas for safety improvements.

## Data Sources
- Motor vehicle crash data (NYC dataset or similar)
- Open datasets for geospatial analysis

## Key Steps in the Project:
1. **Data Exploration**: Understanding and preparing the dataset, handling missing values, and converting columns to appropriate formats.
2. **Time Series Analysis**: Identifying trends and patterns in the data over time (e.g., monthly or hourly crash distributions).
3. **Geospatial Analysis**: Mapping crash locations and creating heatmaps to identify the most accident-prone areas.
4. **Severity Mapping**: Distinguishing between crashes with injuries, fatalities, and no injuries using markers of varying shapes and colors.
5. **Research Question Formulation**: Building custom research questions to explore specific aspects of the data and visualize trends.

## Research Questions:
- What is the distribution of crashes across different boroughs in NYC?
- How do seasonal variations affect the number of crashes?
- What is the trend of crashes over the years and during specific hours of the day?
- Which areas are most prone to severe crashes (injuries or fatalities)?

## Visualizations:
- **Crash Distribution by Borough**: Bar charts comparing crashes across five NYC boroughs.
- **Heatmap of Crash Locations**: Interactive map showing crash density based on latitude and longitude.
- **Time Series Plots**: Identifying trends in the number of crashes over time.
- **Severity Mapping**: Visualizing crash severity (fatalities, injuries) with customized markers.

## Tools and Libraries Used:
- Python, Pandas, Seaborn, Matplotlib, Folium
- Time series analysis using `statsmodels`
- Geospatial analysis using `Folium` for mapping and `HeatMap` for visualizing crash density

## Conclusion
This project provides valuable insights into the patterns and trends of motor vehicle collisions, with a focus on understanding where and when the most severe accidents occur. It aims to inform policy makers and transportation authorities on areas that need intervention to improve road safety.

## How to Run:
1. Clone the repository or download the notebook.
2. Install the required Python libraries (e.g., Pandas, Matplotlib, Seaborn, Folium).
3. Run the Jupyter notebook or any Python IDE to execute the code.

## License
This project is licensed under the MIT License.

## Acknowledgements:
- [NSDC](https://nebigdatahub.org) for providing the data science curriculum and resources.
- Contributors to open datasets and libraries used in the project.
