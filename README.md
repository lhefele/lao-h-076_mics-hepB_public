# Factors associated with hepatitis B vaccination in the Lao People's Democratic Republic: findings from the Multiple Indicator Cluster Surveys in 2011/12 and 2017

<p>This readme file was generated on 2023-07-20 by Lisa Hefele.<br>
Project name: lao-h-076_mics-hepB_public <br>


## Information<br>

In this study, we are investigating factors associated with hepatitis B vaccination in the Lao PDR.<br>

The Multiple Indicator Cluster Survey (MICS) data files from the Lao PDR for the years 2011/12 and 2017 were obtained from the website of UNICEF (https://mics.unicef.org/surveys). Although the MICS data is publicly available, the data is not owned by the authors of this manuscript and therefore not deposited here or on another repository. UNICEF provides information regarding the survey methods in each survey year (https://mics.unicef.org/tools). Data preparation and data analyses were performed in R. <br>


Steps to reproduce the findings of this study:
1. On GitHub, download code files ("Download ZIP")
2. Unzip files on your computer and open R project
3. Obtain the MICS data from 2011/12 (round 4) and 2017 (round 6) from the website of the World Bank or UNICEF
4. Deposit files in folder "data" in a folder corresponding to the survey round
    + Survey round 4 should be saved in a folder called "mics4" in "data"
    + Survey round 6 should be saved in a folder called "mics6" in "data" (Note: survey round 5 does not exist)
5. To generate the research findings from survey round 4, execute code in rmd file "analysis_2012_public"
6. To generate the research findings from survey round 6, execute code in rmd file "analysis_2017_public"

**Note:** <br>
Figure 2 in the manuscript shows the vaccination coverage per province. The sources for the data of the underlying shapefiles and the steps to obtain them are detailed in the code.





## Data & file overview<br>
1. folder "data":
   - file with code for provinces
   - survey data (needs to be obtained from https://mics.unicef.org/surveys)
3. folder "graphs": for figures from manuscript
4. folder "tables": for tables from manuscript
5. rmd file "analysis_2012_public": code to reproduce findings from survey year 4 (2011/12)
6. rmd file "analysis_2017_public": code to reproduce findings from survey year 6 (2017)
