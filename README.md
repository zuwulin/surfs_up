# Surfs Up Company's Pre-Launch Weather Analysis

## Overview of Analysis
The current project was requsted by a start-up company "Surfs Up" in preparation for their upcoming opening.

### Purpose
The purpose of the current project was to investigate the temperature trends across two seasons (i.e., summer and winter) in Hawaii, Oahu, to examine whether the sursf and ice cream shop would have the potential to be successful in the region. The analysis was conducted with the use of SQLite and pandas Jupyter notebook frameworks.

## Results
The results of the data analysis for the both months (June and December, respectively), can be seen below:

<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/165178430-28a771dc-1210-4a82-8f9a-7ba656ffbe1d.png" />
  <img src="https://user-images.githubusercontent.com/99566803/165178449-329c9023-8545-4865-a3ca-cbe2bd6c06be.png" />
</p>

It is important to note that, compared to December, June dataset documented 150 more temperature points. While the difference does, in fact, exist, it should not skew the data between the two points examined significantly.

The main differences between the two months observed are, then, as follows:

* First of all, the mean temperature observed in June is slightly higher (74.9F) than that of December (71F). This should come as no surprise, as summer months are generally expected to produce more heat than the winter months.

* Secondly, the standard deviation (the dispersion of the data) was 0.5 points higher for December (3.74) than for June (3.25), which might imply a significant changes in temperature during December between two neighbouring days.

* Finally, while the maximum temperatures both the two months examined were fairly similar (85F for June and 83F for December), the minimum temperatures were vastly different, with the lowest temperature in June being 64F, and the lowest temperature in December being 56F. This data might suggest that the ice cream demand will most likely drop during the winter season, compared to the summer months.

## Summary
Overall, it is hard to conclude whether the business idea of surf rental and ice cream shop being combined would be successfull year-round in the Oahu region. The summer data suggests that the business idea would be viable, but the December statistics do not strongly suggest a similar picture (in fact, December data might prove the business experiencing a potentially "dry season" in the winter months). In general, I would suggest running some additional analysis (such as the ones proposed below) and "what-if" simulations before fully committing to the project.

### Supporting Analyses Recommendations
* One recommendation that I would suggest in further analysis is to, in addition to the temperature statistics, collect the statistical data outlining the precipitation trends, and analyze this information together.

* Another potential query that would be beneficial is to analyze the temperature (and precipitation) trends more in-depth, by investigating the day-to-day fluctuations, as opposed to the summative month overview. Plotting the data would also help make the data more accesible to any stakeholders involved.
