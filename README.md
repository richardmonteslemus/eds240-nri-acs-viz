# US County FEMA Risk Rating and Index Analysis

## Author: Richard Montes Lemus

## Purpose

The following analysis leverages the Federal Emergency Management Agency's (FEMA) risk index and rating data to visualize US state's county's potential for negative impacts due to natural disasters. It specifically compares California county's risk index and rating to the rest of the United States' counties. 

## File Structure

```         
├── data
│   └── National_Risk_Index_Counties.csv
├── eds240-nri-acs-viz.qmd
├── eds240-nri-acs-viz.Rproj
├── outputs
│   └── eds240-nri-acs-viz.pdf
└── README.md
```

## File Description

-   `eds240-nri-acs-viz.qmd` - Quarto document containing code interpretation and analysis
-   `outputs/` - Folder for rendered pdf
    -   `eds240-nri-acs-viz.pdf` - Final analysis pdf
-   `data/` - Folder containing FEMA risk data
-   `README.md` - This file

## Data Access

The analysis uses the following National Risk Index dataset from the [FEMA](https://www.fema.gov/flood-maps/products-tools/national-risk-index):

## Required Packages

To run this analysis, the following R packages are needed:

-   `tidyverse`
-   `ggtext`
-   `janitor`
-   `here`
  
## References

| Resource | Citation |
|------------------------------------|------------------------------------|
| National Risk Index | Federal Emergency Management Agency (FEMA). (2025). National Risk Index. <https://www.fema.gov/flood-maps/products-tools/national-risk-index> |

## Acknowledgements

The code and content for this analysis comes from the EDS 240 course in the Bren School of Environmental Science and Management Master of Environmental Data Science Program. This course is led by Sam Shanny-Csik and co-led by Annie Adams.
