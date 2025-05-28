# Public Health Data Analysis Portfolio

## Overview
This repository demonstrates proficiency in statistical analysis, data visualization, and public health research using R. The primary analysis examines teenage pregnancy trends across Scottish health boards, showcasing skills in data manipulation, statistical testing, and evidence-based policy recommendations.

## Featured Analysis: Teenage Pregnancy Rates in NHS Lothian (2003-2021)

### Research Question
How do teenage pregnancy rates (TPRs) in NHS Lothian compare to other health boards in Scotland, and what trends can be identified to inform targeted interventions?

### Key Findings
- **Significant reduction**: NHS Lothian's teenage pregnancy rates decreased from 57.7 to 21.0 per 1,000 women aged 15-19
- **Below national average**: Current rates are now below Scotland's national average of 23.2
- **Statistical significance**: Chi-square test confirms genuine trend (χ² = 344.61, p < 0.001)
- **Consistent improvement**: All Scottish health boards show declining trends

### Technical Skills Demonstrated

#### Data Analysis & Statistics
- **Data cleaning and preprocessing** using tidyverse
- **Statistical hypothesis testing** (Chi-square test for count data)
- **Trend analysis** across multiple time points
- **Comparative analysis** between regional health boards

#### Data Visualization
- **Multi-panel bar charts** for regional comparisons
- **Time series line plots** for trend analysis  
- **Statistical comparison plots** (observed vs expected)
- **Professional styling** with consistent color schemes and clear labeling

#### Documentation Best Practices
- **Comprehensive markdown documentation** with clear section headers
- **Inline code comments** explaining analytical decisions
- **Methodology justification** for statistical test selection
- **Critical reflection** on limitations and assumptions
- **Academic referencing** and AI acknowledgment
- **Reproducible analysis** with clear step-by-step workflow

## Repository Structure
```
├── README.md                                    # This file
├── TeenagePregnancyAnalysis.Rmd                # Main R Markdown analysis
├── TeenagePregnancyAnalysis.pdf                # Rendered report
└── ScotPHO_datatab_extract_2024-11-23.csv     # Source data
```

## How to Run This Analysis

### Prerequisites
```r
# Required R packages
install.packages(c("tidyverse", "ggplot2", "knitr", "rmarkdown"))
```

### Running the Analysis
1. Clone this repository
2. Ensure the data file is in the correct directory
3. Open `TeenagePregnancyAnalysis.Rmd` in RStudio
4. Knit the document to generate the PDF report

```r
# Or run directly in R
rmarkdown::render("TeenagePregnancyAnalysis.Rmd")
```

## Data Source
Scottish Public Health Observatory (ScotPHO) - Teenage pregnancy data covering all Scottish health boards from 2003-2021, including rates per 1,000 women aged 15-19 with confidence intervals.

## Methodology Highlights

### Statistical Approach
- **Chi-square test** selected for count data analysis
- **Assumption validation**: Independent observations, adequate sample sizes, mutually exclusive categories
- **Multiple comparison framework** across three strategic time points (2003, 2012, 2021)

### Visualization Strategy
- **Color consistency** across all plots for easy interpretation
- **Reference lines** (national average) for contextual comparison
- **Clear annotations** with statistical results embedded in plots
- **Professional formatting** following data visualization best practices

## Policy Implications
This analysis provides evidence-based insights for public health policy, demonstrating the effectiveness of prevention strategies while identifying areas for continued intervention. The findings support maintaining current approaches while developing targeted support for regions above national averages.

## Critical Reflection
The analysis acknowledges limitations including three-year aggregated data periods, absence of socioeconomic indicators, and potential oversimplification through strategic time point selection. Future work could incorporate spatial analysis and demographic profiling for more targeted interventions.

## About the Author
Public health researcher with expertise in statistical analysis, data visualization, and evidence-based policy development. Committed to transparent, reproducible research practices and ethical use of AI tools in academic work.

---

**Note**: This analysis demonstrates proficiency in R programming, statistical analysis, data visualization, and public health research methodology. All code is thoroughly documented and follows reproducible research principles.
