# A Five Step Approach to Evaluate NYC’s Building Elevation and Subgrade Dataset in Python
Mark Bauer

# Table of Contents
* [1. Introduction](#1-Introduction)
* [2. Notebooks](#2-Notebooks)
* [3. Data](#3-Data)
* [4. Additional Resources](#4-Additional-Resources)
* [5. Say Hello!](#5-Say-Hello)

![grade-floor-mean](figures/grade-floor-mean.png)

![successfully-measured](figures/successfully-measured.png)

# 1. Introduction
On September 20, 2023, NYC's Department of City Planning (DCP) released a press release with the opening line, "City Planning Releases Most Comprehensive Data Set Ever on NYC Building Elevations, Flood Risk." I couldn't wait to get my hands dirty and learn more about this dataset. Spoiler alert: this is in fact an incredible dataset.

The Building Elevation and Subgrade (BES) dataset contains building centroids of Department of Buildings' Building Footprint dataset, and each record contains a grade and first floor measurement for each building (recorded as feet above sea-level in the NADV88 vertical datum) and indicates if subgrade space exists.

I argue for a five step approach to evaluating and learning more about NYC’s Building Elevation and Subgrade Dataset. These steps include:
- 1. Preview Metadata: Examine the shape, counts, columns, data types and null constraints
- 2. Data Coverage: Calculate percentage null of whole dataset, as well as by different groups (e.g. neighborhood)
- 3. Summary Statistics and Visualize: Calculate statistics like min, max, mean, median of key features
- 4. Groundtruth: Compare values against another best available dataset
- 5. Feature Importance and Generalization: Identify features that contribute most to the model and to learn more about a target feature

You can explore the notebooks in the Notebooks section.


# 2. Notebooks
- [1-metadata.ipynb](https://github.com/mebauer/building-elevation-subgrade-nyc/blob/main/1-metadata.ipynb)
- [2-data-coverage.ipynb](https://github.com/mebauer/building-elevation-subgrade-nyc/blob/main/2-data-coverage.ipynb)
- [3-summary-statistics.ipynb](https://github.com/mebauer/building-elevation-subgrade-nyc/blob/main/3-summary-statistics.ipynb)
- [4-nfip-comparison.ipynb](https://github.com/mebauer/building-elevation-subgrade-nyc/blob/main/4-nfip-comparison.ipynb)
- [5-feature-selection.ipynb](https://github.com/mebauer/building-elevation-subgrade-nyc/blob/main/5-feature-selection.ipynb)

# 3. Data
- Official press release: https://www.nyc.gov/site/planning/about/press-releases/pr-20230920.page
- Data on NYC Open Data: https://data.cityofnewyork.us/City-Government/Building-Elevation-and-Subgrade-BES-/bsin-59hv  
- Data on NYC Department of City Planning's website under Waterfront, Climate, & Sustainability Datasets:  
https://www.nyc.gov/site/planning/data-maps/open-data.page


# 4. Additional Resources

# 5. Say Hello!
Feel free to reach out for further discussions.
- LinkedIn: [markebauer](https://www.linkedin.com/in/markebauer/)  
- GitHub: [mebauer](https://github.com/mebauer)  
- Portfolio: [mebauer.github.io](https://mebauer.github.io/)

Keywords: *Building Elevation and Subgrade, Flood Risk, Flood, Flooding, Resiliency, First Floor, First Floor Elevation, First Floor Height, Lowest Adjacent Grade, Subgrade, Basement, New York City, Department of City Planning, Department of Building's, Python, pandas, GeoPandas, Numpy, Matplotlib, Seaborn, Jupyter, Open Data, Open Source, NYC Open Data*.