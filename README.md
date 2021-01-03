# School_District_Analysis

## Overview of the School District Analysis

Maria is the Chief Data Scientist for a city school district system and is responsible for collecting data from each of the schools in her area. Maria was asked to collect student data from standardized test scores for analysis, reporting, and and presentation to investigate performance trends within each of the schools and in total. The purpose of this project is to help Maria analyze student funding and the standardized test scores. To help her, we will gather the data and present various trends of student performance within the different schools. After collecting and presenting the various school and student information, Maria identified patterns of academic dishonesty in Thomas High School within the ninth grade. She requested to update the math and reading scores and replace them with non-applicable values (N/A). After replacing the dishonest data, Maria asked to redo the analysis to include the new null scores in the presentation of the findings. 

## Results

* How is the district summary affected?

The district summary was affected by removing the math and reading scores from ninth grade in Thomas High School. The average math and the average reading scores for ninth graders in Thomas High School both went down a point. The average math score in the original district summary was 79 and the modified summary went down to 78. The average reading score stayed the same. The percentage of students passing math and reading also went down. The original percentage of math was 75% and the modified percentage was 74%. The percentage of students passing reading went down from 86% to 85%. The overall student percentage was the most affected. The overall passing percentage originally was 65% and went down with the value replacement to 64%

* How is the school summary affected?

The school summary was significantly affected by the removal of ninth grade scores from Thomas High School. The score percentages in Thomas High School dropped a significant amount. With the dishonest data, the percentage of students who passed math was 93% and the perentage who passed reading was 97%. With the removal of the fake data, the scores dropped to 66% for math and 69% for reading. The overall percentage score also dropped. In the original data frame, the overall percentage was 90%. In the modified data frame, the overall percentage dropped to 65%

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth grade math and reading scores affected Thomas High School's performance greatly. Without the removal of the false scores, Thomas High School was one of the top performing schools within the city district. With the removal of the scores, the high school became one of the bottom performing schools. 


* How does replacing the ninth-grade scores affect the following:

     * Math and reading scores by grade
     
    The math and reading scores by grade was affected by replacing the ninth-grade scores. Without the         removal of the scores, ninth graders in Thomas High School had one of the highest overall score      
    percentages with 83%. With the removal of the scores, the overall percentage for the ninth grade 
    dropped significantly and was replaced by an N/A score. 
     
     * Scores by school spending
     
    The scores by school spending was affected by the removal of the ninth-grade scores. Without the           removal of the ninth grade scores, the scores for the $630 - $644 spending range was 62.86%. With the     removal of the scores it dropped dramatically to 56.38%.
     
     * Scores by school size
     
   The scores by school size was also affected by the removal of ninth grade scores. Prior to the removal,    medium sized schools had an overall passing percentage of 90.62%. With the removal of the scores, it      dropped to 85.45%.  
   
     * Scores by school type
     
    The scores by school type was affected by the removal of ninth grade scores. Before removing the ninth     grade scores, charter schools had a 90% overall passing percentage. With the removal, Charter schools     dropped down to 87.20%
    
    
## Summary

There are four major changes to the school district analysis after the reading and math scores were replaced. The first major change was the overall score percentages for Thomas High School by grade. Compared to the other schools, without the removal of ninth grade scores, Thomas High School was in the lead for one of the highest overall score percentages within the district. Upon removing the skewed scores, Thomas High School dropped to one of the bottom performing schools. The second major change was the overall score percentage by school spending. The overall percentage for schools within the $630 - $644 spending range significantly dropped in percentage by 6 points. The third major change was the overall percentage by school size. Medium size school score percentages dropped by 5 points with the removal of ninth grade scores. The fourth major change was score percentage by school type. Charter schools dropped their score percentage 3 points but still remain with the highest percentage score by school type. 
