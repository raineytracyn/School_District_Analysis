# School_District_Analysis
### Module 4
# <ins> 1. Overview of the school district analysis: Explain the purpose of this analysis.
#### This analysis was requested due to a schools file showing evidence of academic dishonesty in areas of reading and math for Thomas High School, grade 9th. The purpose of this analysis is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading are replaced scores, verification of clean data, generating a school district summary, and a school summary will be created to produce:
* High and Low performing Schools
* Average Math and Reading Scores by Grade
* Group Scores by School Spending per Student
* Group Scores by School size and type
# <ins> 2. Results: 
## A.Using bulleted lists and images of DataFrames as support, address the following questions.
### i. How is the district summary affected?
#### By looking at the results between the module and challenge work, you can see that the Math and Reading results were inflated by a little over 2% each. This resulted in nearing a percentage difference when looking at the overall passing scores.
###### ![District Affected](https://github.com/raineytracyn/School_District_Analysis/blob/main/Resources/District%20Affected.png)
### ii. How is the school summary affected?
#### Everything from total students to budget stayed consistent. As you look into Math, Reading, and overall numbers, you begin to see the inconsistencies.
###### ![School Summary Affected](https://github.com/raineytracyn/School_District_Analysis/blob/main/Resources/School%20Summary%20Affected.png)
### iii. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### Looking specifically at Thomas High School, you can see the inflated numbers were in the high 80’s and 90’s. By removing fraudulent information, we find the actual scores ranged in the mid-60’s. 
## B. How does replacing the ninth-grade scores affect the following:
### i. Math and reading scores by grade
#### From this angle, you can see the scores have not changed, and “nan” appears in Thomas High Schools 9th grade category. This is likely due to an error written in the code, and will be corrected in 1.1.2 release of the program. Using additional resources supplied, we have a lot of consolidated information to support that there was inaccurate or fraudulent information provided.
###### ![Scores By Grade](https://github.com/raineytracyn/School_District_Analysis/blob/main/Resources/Scores%20by%20Grade.png)
### ii. Scores by school spending
#### You can see in the range of “$630-644” that there was a drop in grades, which parallels the information early on. All other areas have stay consistent.
###### ![Scores by School Spending](https://github.com/raineytracyn/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20spending.png)
### iii. Scores by school size
#### In the medium school size, you can see a drop in grades from the mid 90’s to the mid 80’s. All other school sizes stayed the same.
###### ![Scores By School Size](https://github.com/raineytracyn/School_District_Analysis/blob/main/Resources/Score%20by%20School%20Size.png)
### iv. Scores by school type
#### Looking at the math and reading passing section for charter, there was a dip from the 90’s down to the 80’s, again paralleling over 95% of the results provided above. This brought the overall passing rate down from 90% to 87%.
###### ![Scores by School Type](https://github.com/raineytracyn/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20type.png)
# <ins> 3. Summary: 
## Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
####
