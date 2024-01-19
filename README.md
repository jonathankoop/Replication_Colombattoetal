# “Vaccine Nationalism Erodes Public Trust”: Actual Finding or Faulty Analysis?
## A Verification Report of Colombatto et al.’s (2023): Vaccine Nationalism Counterintuitively Erodes Public Trust in Leaders 


**Attention: Please run Replication_Colombattoetal.Rmd first to automatically download the necessary data and to get access to the R code published by Colombatto et al.**


This project aims to verify the analysis conducted by Colombatto et al. (2023) in their paper on the relationship of vaccine nationalism and public trust in countries' leaders. 

The paper investigates the impact of vaccine nationalism, where better-off countries prioritize domestic vaccination over global distribution, on public trust in leaders. Contrary to policymakers' concerns, the research, based on seven experiments with a total of 4,215 adults across countries with vaccine surpluses (Australia, Canada, UK, US), shows that citizens trust leaders endorsing vaccine redistribution more than nationalistic leaders despite their demographic characteristics.

As our verification target, we selected the coefficient of *condition* (nationalistic vs. redistributive) on trust score in the regression analyses of Studies 1 and 2 as they encapsulate the essence of the study designs and the conclusions drawn. First, studies 1 and 2 were based on the largest sample sizes (2000 and 700 participants, respectively), compared to studies 3 to 7, which had considerably smaller sample sizes, with approximately 300 participants recruited for each study. Second and most importantly, the overarching objective of the entire study was to examine how does vaccine nationalism vs redistribution affect people’s trust in leaders. Studies 1 and 2 laid the foundation for this exploration, serving as the prototypes for subsequent studies. The latter studies presented variations in wordings and scenarios while maintaining similar methods and procedures.

This folder includes the following files and folders:

- **Original_Analysis**: This is an empty folder in which the original analysis are to be stored upon downloading them. This is automatically done when running `Replication_Colombattoetal.Rmd`
  - (Upon running `Replication_Colombattoetal.Rmd`) **S1 - Trust**: This folder contains all documents published by Colombatto et al. on OSF. For rerunning their original analysis run and open `S1 - Analysis`
  - (Upon running `Replication_Colombattoetal.Rmd`) **S2 - Trust YouGov**: This folder contains all documents published by Colombatto et al. on OSF. For rerunning their original analysis run and open `S2 - Analysis`
- **Replication_Colombattoetal.Rmd**: This Rmd-file contains our attempt for verifying whether code reflects the description of the analyses in the paper. **Attention: Run this Rmd to retrieve the Data**

## References
Colombatto, C., Everett, J. A., Senn, J., Maréchal, M. A., & Crockett, M. J. (2023). Vaccine Nationalism Counterintuitively Erodes Public Trust in Leaders. Psychological Science, 34(12), 1309-1321.

