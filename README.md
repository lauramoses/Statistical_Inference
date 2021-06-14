# Investigating the Regulation of Cell Phone Use While Driving and the Proportion of Acccidents Caused by Distracted Driving Per State in 2018

### STAT 3333 Statistical Inference

According to the National Highway Traffic Safety Administration, there were 36,560 people killed in motor
vehicle traffic crashes on U.S. roadways during 2018. The number of fatalities in distraction-affected crashes was 2,841, or 7.8% of total fatalities in 2018. Hand-held cell phone use while driving, namely texting, is one of the most common distracted driving practices, and is especially dangerous for novice drivers. According to the Governors Highway Safety Association (GHSA), 42% of drivers admit to reading a text or email behind the wheel. AT&T, a prominent telecommunications company, advocates “it can wait,” and has encouraged 40,388,681 individuals so far to “take the pledge to never drive distracted,” indicating the widespread problem phone usage while driving presents.

So how can cell phone use while driving be deterred? The GHSA suggests that law enforcement regulation
will help. In particular, the GHSA recommends that states ban hand-held cell phone use for all drivers.
Currently, no state bans all cell phone use for all drivers, but 37 states and D.C. ban all use by novice drivers. 22 states and D.C. prohibit all drivers from using hand-held cell phones while driving. This information led us to investigate the effects of regulating cell phone usage while driving in the United States. 

The National Highway Traffic Safety Administration (NHTSA) is provided with data annually regarding fatal
injuries in motor vehicle traffic crashes from the Fatality Analysis Reporting System (FARS), a nationwide census. FARS keeps track of the cases reported, and has a particular 2018 data set called DISTRACT.csv, which we will be using, that notes whether or not the driver was not distracted, or a code for the type of distraction. In order to analyze our data, we chose to calculate the proportion of distracted accidents to all accidents reported in 2018 for each of 50 states, plus D.C. The FARS Analytic User’s Manual describes the codes, including each state’s code and the method of distraction. For the purposes of this project, we chose codes that were related to cell phone or hand-held use, and omitted codes that were “not distracted” in the calculation of the proportion of distracted driving related accidents. These were codes: 4, 5, 6, 7, 10, 15, 17, 18, 19, 92, 93, 98, 96, 99. Regulated states were selected based on the GHSA List of Distracted Driving Laws by State with laws implemented post 2018 omitted.

Using the proportion of distracted driving accidents as our test statistic, we attempt to answer the following question: do current regulations actually affect the proportion of accidents that occur from distracted driving? We wish to use a permutation test to answer the above question, using the mean difference in proportion of distracted drivers between regulated states unregulated states. Therefore, our null and research hypothesis can be stated as follows:

_H<sub>0</sub>_ : The difference in average proportions of distracted driving accidents between regulated states and nonregulated states is due to chance and insignificant.

_H<sub>A</sub>_ : The difference in average proportions of distracted driving accidents between regulated states and
non-regulated states is statistically significant.

`Keywords: statistical inference, hypothesis testing, bootstrap, permutation, statistical significance`
