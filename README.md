Executive Summary of Project



---
## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**school_code**|int|FRPM & ACT/SAT|The school code is a state number to identify schools. It is how all of the data frames connect.|
|**charter_y_n**|object|FRPM|Yes or No; this school is a Charter School|
|**school_name**|object|FRPM & ACT/SAT|School Name|
|**district_name**|object|FRPM & ACT/SAT|District Name|
|**school_type**|object|FRPM|Type of school: Elementary, Middle, Junior High, High, Alternative, County Community, K-12 Schools, Preschool, Special Education Schools, Youth Authority Facilities, etc..| 
|**enrollment_k12**|object|FRPM|Enrollment of K-12 students at the school.| 
|**free_meal_count_k12**|object|FRPM|Count of students who get free meals in K-12 of the total count of students enrolled.|
|**percent_eligible_free_k12**|object|FRPM|Percent of students eligible for free meals.|
|**frpm_count_k12**|object|FRPM|Total count of students who meet household income or categorical eligibility criteria for free or reduced price meals.|
|**frpm_percent_eligible_k12**|object|FRPM|Percent of students eligible for FRPM.|
|**act_12_enrolled**|float|ACT|Enrollment of student in Grade 12, ACT.|
|**act_num_test_takers**|float|ACT|Number of ACT test takers.|
|**act_num_comp_ge21**|object|ACT|Number of test takers whose ACT Composite Cores are greater than or equal to 21.|
|**act_pct_ge21**|object|ACT|Percentage of test takers whose ACT Composite Cores are greater than or equal to 21.|
|**sat_12_enrolled**|float|SAT|Enrollment of students in Grade 12, SAT.|
|**sat_num_test_takers**|float|SAT|Number of SAT test takers in Grade 12.|
|**sat_tot_num_benchmark**|object|SAT|Total number of students who met the benchmark of ERW and Math in Grade 12.|
|**sat_pct_benchmark**|object|SAT|Percentage of students who met the benchmark of ERW and Math in Grade 12.|



---

### Rubric
Your local instructor will evaluate your project (for the most part) using the following criteria.  You should make sure that you consider and/or follow most if not all of the considerations/recommendations outlined below **while** working through your project.

**Scores will be out of 21 points based on the 7 items in the rubric.** <br>
*3 points per section*<br>

| Score | Interpretation                                                                                                                  |
| ----- | ------------------------------------------------------------------------------------------------------------------------------- |
| **0** | *Project fails to meet the minimum requirements for this item.*                                                                 |
| **1** | *Project meets the minimum requirements for this item, but falls significantly short of portfolio-ready expectations.*          |
| **2** | *Project exceeds the minimum requirements for this item, but falls short of portfolio-ready expectations.*                      |
| **3** | *Project meets or exceeds portfolio-ready expectations; demonstrates a thorough understanding of every outlined consideration.* |

**Project Organization**
- Are modules imported correctly (using appropriate aliases)?
- Are data imported/saved using relative paths?
- Does the README provide a good executive summary of the project?
- Is markdown formatting used appropriately to structure notebooks?
- Are there an appropriate amount of comments to support the code?
- Are files & directories organized correctly?
- Are there unnecessary files included?
- Do files and directories have well-structured, appropriate, consistent names?

**Clarity of Message**
- Is the problem statement clearly presented?
- Does a strong narrative run through the project?
- Does the student provide appropriate context to connect individual steps back to the overall project?
- Is it clear how the final recommendations were reached?
- Are the conclusions/recommendations clearly stated?

**Python Syntax and Control Flow**
- Is care taken to write human readable code?
- Is the code syntactically correct (no runtime errors)?
- Does the code generate desired results (logically correct)?
- Does the code follows general best practices and style guidelines?
- Are Pandas functions used appropriately?
- Does the student demonstrate mastery masking in Pandas?
- Does the student demonstrate mastery sorting in Pandas?

**Data Cleaning and EDA**
- Does the student fix data entry issues?
- Are data appropriately labeled?
- Are data appropriately typed?
- Are datasets combined correctly?
- Are appropriate summary statistics provided?
- Are steps taken during data cleaning and EDA framed appropriately?

**Visualizations**
- Are the requested visualizations provided?
- Do plots accurately demonstrate valid relationships?
- Are plots labeled properly?
- Plots interpreted appropriately?
- Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report?

**Research and Conceptual Understanding**
- Were useful insights gathered from outside sources?
- Are sources clearly identified?
- Does the student provide appropriate interpretation with regards to descriptive and inferential statistics?

**Presentation**
- Is the problem statement clearly presented?
- Does a strong narrative run through the presentation building toward a final conclusion?
- Are the conclusions/recommendations clearly stated?
- Is the level of technicality appropriate for the intended audience?
- Is the student substantially over or under time?
- Does the student appropriately pace their presentation?
- Does the student deliver their message with clarity and volume?
- Are appropriate visualizations generated for the intended audience?
- Are visualizations necessary and useful for supporting conclusions/explaining findings?

In order to pass the project, students must earn a minimum score of 1 for each category.
- Earning below a 1 in one or more of the above categories would result in a failing project.
- While a minimum of 1 in each category is the required threshold for graduation, students should aim to earn at least an average of 1.5 across each category. An average score below 1.5, while it may be passing, means students may want to solicit specific feedback in order to significantly improve the project before showcasing it as part of a portfolio or the job search.


