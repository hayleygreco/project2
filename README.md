Title: Air Quality Analysis: Durham County, NC

Project Description: This project analyzes daily air quality measurements collected from the Raleigh-Durham International Airport (RDU) monitoring station from 2018 through April 2020. The analysis focuses on three air pollutants: CO, PM2.5, and O3. The project includes data cleaning, calculation of yearly minimum and maximum pollutant concentrations, and visualization of monthly pollutant trends.

Data Source: The data were obtained from the U.S. Environmental Protection Agency (EPA) and contain air quality measurements from the RDU monitoring station. The dataset includes daily measurements of CO, PM2.5, and ozone for 2018, 2019, and January through April 2020.

Project Structure:
data/: Contains the original air quality CSV files for 2018, 2019, and 2020.
Project2.Rmd: R Markdown document containing the data cleaning function (clean_air_quality()), data processing, statistical summaries, and visualizations.
README.md: Project description and instructions for reproducing the analysis.
project2.Rproj: RStudio project file.

How to Reproduce the Analysis:
Download or clone this repository from GitHub.
Open project2.Rproj in RStudio.
Ensure the required R packages are installed.
Open Project2.Rmd.
Knit the R Markdown document to generate the Word report.

Required R Packages: tidyverse, knitr, gtsummary, dplyr 

Author: Hayley Greco
Date: November 2026
