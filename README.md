# Denver
Assignments and final project for SES 5294

This forecasting project is for the class SES 5394: Travel Behavior and Forecasting at the Harvard Graduate School of Design. The purpose of this project is to estimate the changes in regional VMT, accessibility, and transit ridership in the Denver-Lakewood-Aurora MSA as a result of increasing Floor Area Ratio (FAR) maximums in multifamily zones. While the MSA continues to develop in a sprawling manner, it is also densifying in many areas and we hope to seek how travel will be impacted as a result. 

Our repository is structured in the following way:

* The _existing_ folder contains data about the existing conditions of the MSA. The markdown file _ExistingConditions.RMD_ contains the code we used to extract census data to create a dataframe including population, housing, employment, and income data. 

* The _alternative_ folder contains data about our proposed conditions (population increase as a result of FAR increases). The _TractZoneOverlay.RMD_ file contains the code we used to determine which tracts contained multifamily zones in each municipality of the MSA. We used the resulting dataframe from that markdown file to calculate the increase in population by tract. The _ComparisonMapsTables.RMD_ file compares the existing conditions with the proposed conditions. We use choropleth maps and summary tables to compare population changes by housing units, income, employment type, household size, and vehicle ownership. 