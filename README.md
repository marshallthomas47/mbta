## MBTA Data Analysis

This is an analysis of MBTA data from July to September of 2016 and 2017. The purpose is to look for any changes in the reliability of the service between these two years.

### Conclusions

- The orange line, in particular, is running slower, with more delays,
in 2017 than in 2016. <a href="https://github.com/marshallthomas47/mbta/blob/master/MBTA_calculations.md" target="_blank">See this analysis for details.</a>
- These increases in delays do **not** appear to be due to platform crowding,
as there does not seem to be a major increase in dwell times on the platforms
from 2016 to 2017. <a href="https://github.com/marshallthomas47/mbta/blob/master/MBTA_dwells.md" target="_blank">See this analysis for details.</a>
- My best guess is that the trains are having more mechanical problems, suggesting a need for better maintenance and more repairs.
- The trains also may have new speed restrictions in the Sullivan / Community
College area that might be involved in the delays.

### Summary of analysis

- The analysis is written in R. There is a separate script (MBTA_LoadData.Rmd) that makes the API calls and stores the data.
- The actual analysis is in MBTA_calculations.Rmd.
- You can view a summary of the results in MTBA_calculations.md.
- An analysis of time on platform (dwell times) can be found in MBTA_dwells.Rmd.
- You can view a summary of the results of that analysis in MBTA_dwells.md.
