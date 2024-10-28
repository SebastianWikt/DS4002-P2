# DS4002-P2: COVID-19's Effect on Demographics Over Time
### Group 5: Neha Channamraju, Sebastian Wiktorowicz (leader), Catherine Young
Research Question: Does the correlation between factors like the migration rate and death rate with life expectancy overtime (2000-2024) have a change point during the time of the COVID-19 pandemic (2019-2021)?

## Software and Platform
- All exploratory code and figures were generated using R
- Install ggplot to create graphs
- Install tidyr to clean the dataet in R
- Running correlation plots were created using the ruptures package in a Google Colab ipynb notebook

## Map of Documentation
DS4002-PI
- LICENSE.md
- README.md
- Data
  - IDB_10-21-24.csv
- Output
    - Exploratory graphs
    - Running correlations.pdf
- Scripts
    - MIL2-P2.Rmd
    - MIL2-P2.Pdf
    - Project_2_running_corr.ipynb
- References
[1] “International database,” United States Census Bureau, https://www.census.gov/data-tools/demo/idb/#/table?COUNTRY_YEAR=2024&COUNTRY_YR_ANIM=2024  (accessed Oct. 7, 2024). 
[2] Tomov L, Chervenkov L, Miteva DG, Batselova H, Velikova T. “Applications of time series analysis in epidemiology: Literature review and our experience during COVID-19 pandemic.” World J Clin Cases. 2023 Oct 16;11(29):6974-6983. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10631421/ (accessed Oct. 9, 2024).

## Instructions for reproducing results
Running the code in the scripts folder will generate the plots and analysis that we used for our inferences in this project. 

### Exploratory correlational graphs
- Install the necessary packages in R
- Clone this repository for access to the dataset (both cleaned data and original dataset).
- Set the working directory in the R file as the location where you downloaded the .rmd file.
- Download the data from the Data folder into the same working directory from the previous step.
- Read in and clean the data.
- Run the defined functions to reproduce data and graphs.
- Determine the correlation between the variables highlighted in the code from the dataset

### Change point analysis graphs
- Install ruptures package in Colab and follow the code to produce the change point graphs
- Window size can be adjusted to the minimum value with no errors/gaps in the graph
- x and y can be adjusted to look for different correlations from the variables in the census dataset
- The time scale on the x axis going from 0-390 represents the years 2000-2024, so the COVID19 pandemic would have started at about 310

Refer to comments throughout the code script in the Scripts folder for specific instructions that will guide you through reproducing our results.
