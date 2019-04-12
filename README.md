```
                     ________                            
M               M   /_  __/ /  ___                       
M M           M M    / / / _ \/ -_)                      
M M M       M M M   /_/_/_//_/\__/         __        ____
M M M M   M M M M     /  |/  /__ ________ / /  ___ _/ / /
M M M M M M M M M    / /|_/ / _ `/ __(_-</ _ \/ _ `/ / /
M M M M M M M M M   /_/__/_/\_,_/_/ /___/_//_/\_,_/_/_/  
M M M M M M M M M     / _ \_______    (_)__ ____/ /_     
M M M M M M M M M    / ___/ __/ _ \  / / -_) __/ __/     
M M M M M M M M M   /_/  /_/  \___/_/ /\__/\__/\__/     
                                 |___/  
```

By [Andrew R. Calderon](https://www.themarshallproject.org/staff/andrew-r.-calderon)

# More Detained Migrants Give Up Court Fights and Leaving the U.S.
Under the Trump administration, a growing number of detainees in immigration detention centers are choosing to depart voluntarily rather than fight court cases. These so-called "voluntary departures" have been trumpeted by the Department of Justice as a sign of successful enforcement.

But attorneys and former immigration judges suspect that many immigrants with legitimate fear claims are choosing to return to dangerous circumstances, rather than languish in indefinite detention while their cases work their way through an unprecedentedly clogged court system.

The Marshall Project analyzed voluntary departure applications data from the Executive Office of Immigration Review (EOIR), the office at the Department of Justice responsible for overseeing the immigration courts, to answer the following questions:


1. Are voluntary departure applications increasing under the Trump administration?  


2. Which courts have seen the greatest increases in the amount of voluntary departure applications from 2016 to 2018?   

Our story, "[More Detained Migrant Give Up Court Fights and Leaving the U.S](https://www.themarshallproject.org/2019/04/15/more-detained-immigrants-are-giving-up-court-fights-and-leaving-the-u-s)" published by [The Marshall Project](http://themarshallproject.org) on April 15, 2019, examined the change in voluntary departure applications across the immigration system since Trump was elected into office.

Included in this repo is [the table](data/df_monthly_vdeparture_applications_2012_2018.csv) of data The Marshall Project used to analyze and visualize the influx of voluntary departure applications. These are voluntary departure applications for 63 base city locations where there are immigration courts, by month and year, from Oct. 2011 to Dec. 2019.

If you'd like to use the data, please read on to understand its provenance.

# Data Sources and Methodology

Before any analysis could be done, we joined multiple data tables that we received from EOIR into one table. We had to clean up column names and account for missing values at various locations. After multiple conversations with EOIR's FOIA office, we were confident that we had all available data for all available facilities. Only then could we move on to the analysis.

We started the analysis with a deductive approach. We plotted voluntary departure applications by year to observe overarching trends in the data. We found that from 2017 to 2018, the number of applications filed had not only doubled, but it had also reached a six-year high.

From there, we took apart the yearly data by month. We found that the upward trend in applications started in 2016, around the onset of the Trump administration.

![Voluntary Departure Applications, by month, from 2012 to 2018](https://github.com/themarshallproject/eoir_voluntary_departures_applications/blob/master/plots/Voluntary_Departure_Applications_by_Month.png)

These observations comported with on-the-ground reporting, and helped to provide broader context for the story of Alejandra García Zamarrón, a mother of three U.S. citizens who opted for voluntary departure instead of remaining in detention in Atlanta, despite fear of reprisal from her spouse in Mexico.

The chart for the final story was handcrafted by Katie Park. She also provided input to ensure that the data visualization effectively communicated all the right information, in the best and simplest way.

All of our analysis was done using R, an open source language and environment for statistical computing and graphics. And our data came from FOIA requests to EOIR, and data from the Transactional Access Records Clearinghouse, or TRAC, at Syracuse University.


# Contributors
It takes a village to raise a data story. This one benefitted from the scrutiny, creativity and talents of:

- [Christie Thompson](https://www.themarshallproject.org/staff/christie-thompson), Staff Writer, at The Marshall Project
- [Andrew R. Calderon](https://www.themarshallproject.org/staff/andrew-r.-calderon), Data Reporter, at The Marshall Project
- [Anna Flagg](https://www.themarshallproject.org/staff/anna-flagg), Senior Data Reporter, at The Marshall Project
- [Katie Park](https://www.themarshallproject.org/staff/katie-park), Developer, at The Marshall Project
- [Alex Tatusian](https://www.themarshallproject.org/staff/alex-tatusian), Editorial Designer, at The Marshall Project
- [Tom Meagher](https://www.themarshallproject.org/staff/tom-meagher), Managing Editor for Digital and Data, at The Marshall Project


# Questions, Comments?
We love feedback: acalderon@themarshallproject.com

If you want access to the raw data compiled via FOIAs and TRAC, feel free to contact us.

If you wish to receive our roundups of the best criminal justice news from around the web, please [subscribe to our daily newsletter](https://themarshallproject.us3.list-manage.com/subscribe?u=a92567c13cca06b470824aead&id=5e02cdad9d).
