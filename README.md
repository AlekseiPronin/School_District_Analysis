# School_District_Analysis

## Project Overview

This project was aimed to analyse data of student funding and students' standardised test scores using Pandas. Names of students and their test scores for math and reading for different grades were provided in .csv file. Also, the various information about names of the schools, type, size and budget was provided in separate .csv file. The task was in merging two .csv files, aggregating the data and showcasing trends in school performance, which can be used for making decisions regarding school's budgets and priorities.

## Results

### Initial Analysis

The District Analysis was broken down into several steps: 
  1) District Summary Analysis. It contained the total count of students, total budget of schools, average test scores and percentage of those who passed tests.
  2) School Summary Analysis. The same metrics were applied to show information of every school with addition of budget for each student.
  3) High and Low Performing Schools. All the schools were listed based on overall test passing percentage.
  4) Test Scores by Grade. The data was organized to visualise the performance of each grade in every school.
  5) Scores by School Spending. The spending range per student was applied to find out the average score and passing percentage based on spending range.
  6) Scores by School Size. This analysis aimed to show average score and passing percentage based on the size of every school.
  7) Scores by School Type. The aim was to show the performance based on school type (Charter or District)

### The Second Analysis

According to the task, we were asked to remove the math and reading scores of 9th grade in Thomas High School and perform the same analysis with fresh data to find out if it affected previous results.

The results as follows:
  1) District Summary. 
    pic1 before
    pic2 after
    The average passing score and passing percent decreased by 0.1-0.3%
  2) School Summary.
    pic1 before
    pic2 after
    The average math score for Thomas High School decreased 0.06%, reading score increased 0.05%, percentage passing math decreased 0.09%, percentage passing reading and overall passing both exams decreased by almost 0.3%
  3) After removing exams results for 9th grade of Thomas High School, its position relative to other schools remained the same second best performing school.
    pic 1
    pic2
  4) After removing scores of 9th graders, the math and reading scores was displayed as NaN
    pic1
    pic2
    pic1 
    pic2
  5) 
