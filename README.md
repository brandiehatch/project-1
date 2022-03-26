# Executive Summary of Project

### Problem Statement

Project hypothesis: students in low-income school districts are not meeting/exceeding the benchmark for SAT Math, Evidence-Based Reading & Writing (ERW), and ACT composite scores. 
This project aims to explore a possible correlation between the districts with the most Free and Reduced-Priced Meal participation and their scores on the ACT and SAT so that Title I program leaders can determine funding or grant eligibility. These grants and funding sources could help improve ACT and SAT scores of children from low-income families to help ensure that all children meet challenging state academic standards.

---
### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**school_code**|*integer*|FRPM & ACT/SAT|The school code is a state number to identify schools. It is how all of the data frames connect.|
|**charter_y_n**|*object*|FRPM|Yes or No; this school is a Charter School|
|**school_name**|*object*|FRPM & ACT/SAT|School Name|
|**district_name**|*object*|FRPM & ACT/SAT|District Name|
|**school_type**|*object*|FRPM|Type of school: Elementary, Middle, Junior High, High, Alternative, County Community, K-12 Schools, Preschool, Special Education Schools, Youth Authority Facilities, etc..| 
|**enrollment_k12**|*integer*|FRPM|Enrollment of K-12 students at the school.| 
|**free_meal_count_k12**|*integer*|FRPM|Count of students who get free meals in K-12 of the total count of students enrolled.|
|**percent_eligible_free_k12**|*float*|FRPM|Percent of students eligible for free meals.|
|**frpm_count_k12**|*integer*|FRPM|Total count of students who meet household income or categorical eligibility criteria for free or reduced price meals.|
|**frpm_percent_eligible_k12**|*float*|FRPM|Percent of students eligible for FRPM.|
|**act_12_enrolled**|*float*|ACT|Enrollment of student in Grade 12, ACT.|
|**act_num_test_takers**|*float*|ACT|Number of ACT test takers.|
|**act_num_comp_ge21**|*float*|ACT|Number of test takers whose ACT Composite Cores are greater than or equal to 21.|
|**act_pct_ge21**|*float*|ACT|Percentage of test takers whose ACT Composite Cores are greater than or equal to 21.|
|**sat_12_enrolled**|*float*|SAT|Enrollment of students in Grade 12, SAT.|
|**sat_num_test_takers**|*float*|SAT|Number of SAT test takers in Grade 12.|
|**sat_tot_num_benchmark**|*float*|SAT|Total number of students who met the benchmark of ERW and Math in Grade 12.|
|**sat_pct_benchmark**|*float*|SAT|Percentage of students who met the benchmark of ERW and Math in Grade 12.|



---

### Analysis Sumamry

The correlation analysis, scatterplot, and heatmap all confirmed that there is a negative correlation between the Percent of students eligible for FRPM. As the data shows, the higher the number of students eligible for FRPM, the lower the ACT/SAT tests scores will be.

---

### Conclusions and Recommendations

In conclusion, there is a correlation between students who are eligible for Free and Reduced-Price Meals and those students who score low on the ACT or SAT. Additionally, many eligible students do not even take the ACT or SAT. 

I recommend that the ACT and SAT exam provide give free access to the tests for all students in FRPM eligible schools and for all students who are eligible for FRPM in any school. Make the free assessments as accessible as possible for students eligible for FRPM so that it is easy to take the assessments.

Additionally, I recommend that the State of California, the Federal Government, and other funding providers continue to provide financial assistance to the schools and districts with the most participants in the Free or Reduced-Priced Meal (FRPM) program. This would include funding to provide study resources and practice test opportunities.

---

### Sources

* Income Eligibility Guidelines can be found from the Food and Nutrition Service Agency of the United States of America: https://www.federalregister.gov/documents/2018/05/08/2018-09679/child-nutrition-programs-income-eligibility-guidelines
* Free or Reduced-Price Meal School-level Data and [Data Dictionary](https://www.cde.ca.gov/ds/ad/filesspfrpm.asp) can be found on the California Department of Education website: https://www.cde.ca.gov/ds/ad/filessp.asp 
* U.S. Department of Education Title I, Part A website: https://www2.ed.gov/programs/titleiparta/index.html 
* National Center for Education Statistics: https://nces.ed.gov/blogs/nces/post/understanding-school-lunch-eligibility-in-the-common-core-of-data 
* No Kid Hungry: Center for Best Practices: https://bestpractices.nokidhungry.org/ 


