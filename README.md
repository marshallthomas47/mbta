## MBTA Data Analysis

This is an analysis of MBTA data from July to September of 2016 and 2017. The purpose is to look for any changes in the reliability of the service between these two years.

### Conclusions

- The orange line, in particular, is running slower, with more delays,
in 2017 than in 2016.
- These increases in delays do **not** appear to be due to platform crowding,
as there does not seem to be a major increase in dwell times on the platforms.
- My best guess is that the reliability of the system is dropping, suggesting
a need for repairs.
- The trains also may have new speed restrictions in the Sullivan / Community
College area that might be affecting this. 

### Summary of analysis

- The analysis is written in R. There is a separate script (MBTA_LoadData.Rmd) that makes the API calls and stores the data.
- The actual analysis is in MBTA_calculations.Rmd.
- You can view a summary of the results in MTBA_calculations.md.
- An analysis of time on platform (dwell times) can be found in MBTA_dwells.md.
