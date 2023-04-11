### Data Wonders Group - Project 1

Drug addiction and specifically, opioid abuse, is becoming a significant social issue in the US.  A preliminary examination of available data from CDC indicates that there is a steady increase in death via opioid overdose from 2011 to 2017 time frame.   Overall goal of the data analysis is to understand drivers of death from opioid abuse and identify areas where funds and efforts should be dedicated to reduce drug abuse and subsequent death rates.


Data available from CDC was analyzed using python for Pandas and Jupyter notebook.  Total death count for each year from 2011 to 2017, at US level and state level, was extracted using groupby and loc functionality in python and its variation with income level as well as educational level was investigated.  In addition, ranking of death levels by state as well as state’s corresponding population was also examined.  All of the extracted data was then exported to excel to prepare linear regression plots.


Data analysis thus far reveals that there is linear relationship between drug use and income levels, as well as education level.  Generally, drug use increased with increasing income and increasing education but a deeper dive is needed to understand if the correlation exists by coincidence or if there is a causation here.  Analysis at a state/regional level is also needed to understand the trends at a lower level.  


Finally,  for path forward, there are other important factors such as subject’s gender, age and employment status which was not available in the dataset used. It would be of value to have access to data which shows impact of subject’s gender, age and employment level.   Further, the data is somewhat dated, about 6 years old and does not have information during and after COVID.  There has been a game changing impact on opioid abuse, post COVID. Therefore, additional data will need to be included in the study to have a complete overview of the crisis.


Another recent data source (yahoo.com and CDC) show that the death rate increased exponentially post COVID, more than doubling versus 2017 timeframe.  Therefore, impact of COVID as is needed to determine if the spike was temporary or something has changed fundamentally and permanently. 


An expanded exploratory work will help in establishing the key factors responsible for driving drug abuse.  Social organizations and governmental authorities can then focus on those factors to  optimize efforts for curbing deaths via drug abuse.
