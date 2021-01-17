# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis


### Problem Statement


College applications are a stressful process that each high school students need to go through if they want to pursue higher education. With all the requirements and actual work demanded from students, it's easy to be unsure or even a little bit lost.

My job is to guide students, help them understand the process, especially when it comes to standardized tests (SAT and ACT).
Based on aquired data and a thorough analysis, I'll explain to them all they need to do in order to meet their own expectation when it comes to college choice and also the majors they pick.

#### Data Dictionary 

Based on the data provided, I utilized several dataframes and had to clean up the data in order to perform the exploratory analysis. I mainly had to change the type of certain columns to float or integer per exemple. 

I used the intended college majors data frame to understand the trends, popularity of certain fields. I also used the SAT and ACT scores by colleges dataframe. It gave me an insight on the requirements in terms of grades for each colleges where I had information. I had to clean up the data as well, change data types, I separated the 25th and 75th percentile into two separate columns in order to show the students the minimum score to aim for each colleges.



|Feature     | Type      | dataset   | Description          |
|------------|-----------|-----------|----------------------|
|  school    | object    | college_set | Name of the college| 
  applies_class_years | int64 |  college_set | years in which the policies apply to 
  policy_details | object | college_set | requirements per colleges for acceptance
  number_of_applicants | int64 | college_set | number of person that applied to this particular college
  accept_rate | float | college_set | The rate of acceptance for each colleges
  sat_total_25th_percentile | float | college_set |25th percentile SAT score for each colleges
  sat_total_75th_percentile | float |college_set |75th percentile SAT score for each colleges
  act_total_25th_percentile | float | college_set |25th percentile ACT score for each colleges
  act_total_75th_percentile	| float | college_set |75th percentile ACT score for each colleges
  test_is_optional | int64 | college_set | value indicating if the standardized test are optional for each college
  intended_college_major | object | intended_majors |name of college major
  test_takers | int64 | intended_majors | number of student applying for the corresponding major
  percent | float | intended_majors | percentage of students that applied to the corresponding major
  total | int64 | intended_majors | combined score SAT score
  reading_writing | int64 | intended_majors | reading and writing SAT score 
  math | int64 | intended_majors | math SAT score 




#### Conclusion

The majority of the colleges studied in this analysis have an optional test policy and only 6% of these colleges required a test for admission.

Even though these standardized test are no longer mandatory going forward; I would still advise students to take the test to increase their chance to reach their desired colleges and majors. Especially for those wanting to go to California; where the colleges have the most applicant.

I would also tell them to focus on the 75th percentile of the school they want to get into to have the most chance to get in. 95% of the SAT 75th percentile score for the colleges are between 1136.8 and 1582.4 and between 23.6 and 36.2.

I would advise any applicants to reach for a minimum of 1200 for the SAT and 24 for the ACT combined score. STEM and Business majors have the most applicants and the highest SAT/ACT scores in math and reading.

I would advise students to have good score across discipline even if you're not interested in a science or business major as math is an important part of the test.
