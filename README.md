# School_District_Analysis

## Project Overview

This project was aimed to analyse data of student funding and students' standardised test scores using Pandas. Names of students and their test scores for math and reading for different grades were provided in .csv file. Various information about names of the schools, type, size and budget was provided in separate .csv file. The task was in merging two .csv files, aggregating the data and showcasing trends in school performance, which can be used for making decisions regarding school's budgets and priorities.

## Results

### Initial Analysis

The District Analysis was broken down into several steps: 
  1) District Summary Analysis. It contained the total count of students, total budget of schools, average test scores and percentage of those who passed tests.

   ![Before](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/District_Summary_1.png)
   
  2) School Summary Analysis. The same metrics were applied to show information of every school with addition of budget for each student.

   ![Before](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/School_Summary%20_1.png)
   
  3) High and Low Performing Schools. All the schools were listed based on the overall test passing percentage.

  Top Schools 
  
  ![Top](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Top_Schools_1.png)
  
  Bottom Schools
  
  ![Bottom](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Bottom_Schools_1.png)
    
  4) Test Scores by Grade. The data was organized to visualise the performance of each grade in every school.

  Math
  
   ![Math before](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Math_Scores_by_Grade_1.png)
    
  Reading
  
   ![Reading before](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Reading_Scores_by_Grade_1.png)

  5) Scores by School Spending. The spending range per student was applied to find out the average score and passing percentage based on spending range.

  ![By spending](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Scores_by_school_spending_1.png)

  6) Scores by School Size. This analysis aimed to show average score and passing percentage based on the size of every school.

  ![By size](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Scores_by_school_size_1.png)

  7) Scores by School Type. The aim was to show the performance based on school type (Charter or District)

  ![By type](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Scores_by_school_type_1.png)



### The Second Analysis

According to the task, we were asked to remove the math and reading scores of 9th grade in Thomas High School and perform the same analysis with fresh data to find out if it affected previous results.

The results as follows:

  1) District Summary. 
    
   ![After](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/District_Summary_2.png)
    
   The average passing score and passing percent decreased by 0.1-0.3%
   
  2) School Summary.
    
   ![After](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/School_Summary_2.png)
      
   The average math score for Thomas High School decreased by 0.06%, reading score increased by 0.05%, percentage passing math decreased by 0.09%, percentage passing reading and overall passing both exams decreased by almost 0.3%
   
  3) After removing exams results for 9th grade of Thomas High School, its position relative to other schools remained the same second best performing school.
    
  ![After](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Top_Schools_2.png)
    
  4) The math and reading scores was displayed as NaN
   
   Math 
   
   ![Math after](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Math_Scores_by_Grade_2.png)
    
  Reading
  
   ![Reading after](https://github.com/AlekseiPronin/School_District_Analysis/blob/main/Resources/pics/Reading_Scores_by_Grade_2.png)
    
  5) Scores by School Spending, by School Size and by School Type changed by 0.01% and remained the same after formatting, which means removing exams results had insignifficant effect on these scores


## Summary 

To sum up, removing scores of 9th grade of Thomas High School had overall slight effect on the previous results, for example: The average passing score and passing percent decreased by 0.1-0.3%; the average math score for Thomas High School decreased by 0.06%, reading score increased by 0.05%, percentage passing math decreased by 0.09%, percentage passing reading and overall passing both exams decreased by almost 0.3%; the position of Thomas High School relative to other schools remained unchanged; Scores by School Spending, by School Size and by School Type remained the same after formatting.
