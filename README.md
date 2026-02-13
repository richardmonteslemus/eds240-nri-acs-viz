# US County FEMA Risk Rating Across US States and Racial and Ethnic Groups

## Author: Richard Montes Lemus

## Purpose

The following analysis visualizes natural disaster risk across different US states and racial/ethnic groups. 

Part 1: 
This analysis leverages the Federal Emergency Management Agency's (FEMA) risk index and rating data to visualize the potential for negative impacts due to natural disasters across US counties. It specifically compares California counties' risk index and rating to the rest of the United States.


Part 2: 
This analysis leverages FEMA's risk rating data and the United States Census Bureau's American Community Survey (ACS) data to visualize risk ratings across different racial/ethnic groups in California.


## File Structure

```
├── data
│   ├── ACS-1yr-2023-county-race-ethnicity.csv
│   └── National_Risk_Index_Counties.csv
├── eds240-acs-viz.qmd
├── eds240-nri-acs-viz.Rproj
├── eds240-nri-viz.qmd
├── outputs
│   ├── eds240-acs-viz.pdf
│   └── eds240-nri-viz.pdf
└── README.md
```


## File Description

-   `eds240-nri-viz.qmd` - Quarto document containing code interpretation and analysis for FEMA risk data
-   `eds240-acs-viz.qmd` - Quarto document containing code interpretation and analysis for FEMA risk data and ACS data
-   `outputs/` - Folder for rendered pdfs
    -   `eds240-nri-viz.pdf` - FEMA risk final analysis pdf
    -   `eds240-acs-viz.pdf` - FEMA risk and ACS final analysis pdf
-   `data/` - Folder containing FEMA risk data and ACS data
-   `README.md` - This file

## Data Access

The analysis uses the following National Risk Index dataset from [FEMA](https://www.fema.gov/flood-maps/products-tools/national-risk-index) and [ACS](https://www.census.gov/programs-surveys/acs/about.html).



## Required Packages

To run this analysis, the following R packages are needed:

-   `tidyverse`
-   `ggtext`
-   `janitor`
-   `here`
  
## References

| Resource | Citation |
|------------------------------------|------------------------------------|
| National Risk Index | Federal Emergency Management Agency (FEMA). (2023 and 2025). National Risk Index. <https://www.fema.gov/flood-maps/products-tools/national-risk-index> |
| American Community Survey | The United States Census Bureau. (2023). American Community Survey. <https://www.census.gov/programs-surveys/acs/about.html> |


## Acknowledgements

The code and content for this analysis comes from the EDS 240 course in the Bren School of Environmental Science and Management Master of Environmental Data Science Program. This course is led by Sam Shanny-Csik and co-led by Annie Adams.
