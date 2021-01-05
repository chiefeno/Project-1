# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis


### Problem Statement


College applications are a stressful process that each high school students need to go through if they want to pursue higher education. With all the requirements and actual work demanded from students, it's easy to be unsure or even a little bit lost.
My job is to guide students, help them understand the process, especially when it comes to standardized tests (SAT and ACT).
Based on aquired data and a thorough analysis, I'll explain to them all they need to do in order to meet their own expectation when it comes to college choice and also the majors they pick.

#### Data Dictionary 

Based on the data provided, I utilized several data frames such as the SAT and ACT results for all the states.
I had to clean up the data in order to perform the exploratory analysis. I mainly had to change the type of certain columns to float or integer per exemple. I also used the intended college majors data frame to understand the trends, popularity of certain fields. Last but not least, the SAT and ACT scores by colleges data frame. It gave me an insight on the requirements in terms of grades for each colleges where I had information. I had to clean up the data as well, change data types, I separated the 25th and 75th percentile into two separate columns in order to show the students the minimum score to aim for each colleges.
I also separated all the colleges into three tiers based on their acceptance rate and 25th percentile.


| Feature     | Type      | dataset   | Description           |
|-------------|-----------|-----------|-----------------------|
|  State      | object    |  act_2019 | location where        | 
|             |           |           | the data was          |
|             |           |           | collected             |
|-------------|-----------|-----------|-----------------------|
|participation| object    | act_2019  | rate of participants  |
|-------------|-----------|-----------|-----------------------|
| Composite   | float64   | act_2019  | average score ACT     |
|-------------|-----------|-----------|-----------------------|
|  date       | object    |  act_2019 | year when             | 
|             |           |           | the data was          |
|             |           |           | collected             |
|-------------|-----------|-----------|-----------------------|
|  State      | object    |  sat_2019 | location where        | 
|             |           |           | the data was          |
|             |           |           | collected             |
|-------------|-----------|-----------|-----------------------|
|participation| object    | sat_2019  | rate of participants  |
|-------------|-----------|-----------|-----------------------|
| Evidence    |           |           |                       |
| based       |           |           |                       |
| reading     |           |           |                       |
| and writing | int64     | sat_2019  | SAT score of reading  |
|             |           |           | and writing           |
|-------------|-----------|-----------|-----------------------|
| Math        | int64     | sat_2019  | Math score SAT        |
|-------------|-----------|-----------|-----------------------|
|  Total      | int64     |  sat_2019 | sum of Math           | 
|             |           |           | and evidence based    |
|             |           |           | writing               |
|-------------|-----------|-----------|-----------------------|


#### Conclusion

Based on my analysis; I would say that the entrance to college is competitive.
Even though there are a lot of colleges; to maximize their outcome students should aim high.
79% of all applicants chose between 10 majors over 38 majors available.
The trend demonstrated by the scatter plot also show that the highest number of applications are received by top tier college.
On average the SAT scores for the year nationwide is 1113 and 21.4 for the SAT and those scores barely can get you into a tier 2 college ! While standardized test are optional in many cases; why not stand out and take one of the test ?
The final word is to maximize your chances by working hard; setting up a higher goal for yourself and apply to many colleges as possible because you might not get your first choice !

