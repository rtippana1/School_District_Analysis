# Stchool District Analysis

## Overview of Project
Chief data scientist for city school district is responsible for analyzing information from a variety of sources and then variety of formats.In this role she is tasked  to preparing all standardized test data for analysis recording and presentation to provide insights about performance trends and patterns.These insights are used to inform discussion on strategic decision at school and district level. 
In this project i am helping maria to analyze data on student funding and student standardized test scores. Access to every student’s math and reading scores and various other information on the schools they attend.
Aggregate the data and show cases trends in school performance.This analyze will assist school board and superintendents in making decisions reg the school budgets and priorities.
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered.Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards.In order to uphold the state testing standards we have replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and perfrom the school district analysis.

### Results
 **school district summary Data Frame**
 
  - The school district summary Data Frame before ignoring the reading and math grades for Thomas High School ninth graders.

  
      ![](images/Old%20District%20Summary%20DF.png)
      
  - The school district summary Data Frame after ignoring the reading and math grades for Thomas High School ninth graders.
  
      ![](images/New%20District%20Summary%20DF.png)
      
 - Impact of removing the reading and math grades for Thomas High School ninth graders has not made much impact on **school District summary Data Frame**
 
     1.**Total number of students:** There is no impact on the number of students after ignoring the reading and math grades for Thomas High School ninth graders.
     
     2.**Total number of schools:** There is no impact on the number of schools after ignoring the reading and math grades for Thomas High School ninth graders.
     
     3.**Total budget:** There is no impact on the Total budget after ignoring the reading and math grades for Thomas High School ninth graders.
     
     4.**Average math score:** The average math score after ignoring the reading and math grades for Thomas High School ninth graders is 78.9 whereas score  before ignoring was 79.0.
     
     5.**Average reading score:** The average reading score after ignoring the reading and math grades for Thomas High School ninth graders is 81.9 and score before ignoring was 81.9 hence no change.
     
     6.**Percentage of students who passed math:** The % passing math after ignoring the reading and math grades for Thomas High School ninth graders is 74.8 and before ignoring was 75.
     
     7.**Percentage of students who passed reading:** The % passing Reading after ignoring the reading and math grades for Thomas High School ninth graders is 85.7 and before ignoring was 86.
     
     8.**Overall passing percentage:** The % Overall Passing after ignoring the reading and math grades for Thomas High School ninth graders is 64.9 and before ignoring was 80.
  


#### Summary
 
- Impact of removing the reading and math grades for Thomas High School ninth graders has not made much impact on **school summary Data Frame**

  
   - The school summary Data Frame before ignoring the reading and math grades for Thomas High School ninth graders
  
      ![](images/Old%20School%20Summary%20DF.png)
      
   - The school summary Data Frame after ignoring the reading and math grades for Thomas High School ninth graders
  
      ![](images/New%20School%20Summary%20DF.png)

1.Based on the above values removing the reading and math grades for Thomas High School ninth graders has made an impact only to the Thomas High School KPIs and has not had any impact on other schools in the school summary Data Frame.

2.**% passing math:** Before replacing the ninth graders’ math scores the % passing math  was 93.272 where as after replacing the math score the % passing math of Thomas High School has reduced to 66.911.

3.**% passing reading:** Before replacing the ninth graders’ reading scores the % passing reading was 97.308 where as after replacing the reading score the % passing reading of Thomas High School has reduced to 69.663.

4.**overall passing %:** Before replacing the ninth graders’ reading and math scores the %overall passing was 90.948 where as after replacing the reading and math scores the %overall passing of Thomas High School has reduced to 65.077.

