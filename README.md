# Data visualiation on fish activity depending on ocean acidic properties
### Project information
The project focuses on fish activity depending on ocean acidification. This project aims to demonstrate extensive R programming focusing on data wrangling, visualisation and useful statistics for data analysis.

The analysis reviews the conclusion drawn from Clark et al (2020) in the paper "Ocean acidification does not impair the behaviour of coral reef fishes" where the authors contradicts the idea that increasing ocean CO2 levels increases susceptibility of coral reef fishes from behavioural and sensory impairments (i.e., Clark et al writes that ocean acidification has negligible effects on coral reef fish behaviour). Thus, the paper documents a three-year long study where they assess the number of seconds the fish remains active per minute, averaged across the duration of the study, in relations to the species and levels of CO2 in the water.

 
The file used is called: "OA_activitydat_20190302_BIOL3207.csv". We looked at this dataset to find discrepencies in the original hypothesise that was established by the authors.

The data file is a CSV file with 9 columns. While 3 of these are ignored ('...1', 'loc', 'comment') in this analysis, the rest gives information on fish activity depending on the acidification of the water. All 6 species underwent either a control or CO2 treatment, and their "sl" and "activity" were measured. 

### General workflow
After establishing the workpath, data wrangling was done to clean unnecessary data. The data was also summarised based on numerical information of different treatments and species. 
