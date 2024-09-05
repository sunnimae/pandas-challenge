OVERVIEW
To analyze the district-wide standardized test results. Access will be provided to every student's math and reading scores, along with various details about the schools they attend. The objective is to aggregate the data and highlight evident trends in school performance.

TOOLS:
Pandas and Jupyter Notebook

OBJECTIVE: 
Aggregate the data and highlight evident trends in school performance. Create a report that includes the following data:

  District Summary
  Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame. The summary should feature:
    - Total number of unique schools
    - Total students
    - Total budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

  School Summary
  Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school. The metrics should feature:
    - School name
    - School type
    - Total students
    - Total school budget
    - Per student budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)
    - Highest-Performing Schools (by % Overall Passing)
    - Lowest-Performing Schools (by % Overall Passing)
    - Math Scores by Grade
    - Reading Scores by Grade
    - Scores by School Spending

ANALYSIS:
The size of the school is more important than the spending per capita. Schools with 4000 students or more are less efficient in allocating their funds. They require more spending per capita yet tend to score lower in the overall passing rate. This may be because larger schools have more infrastructure to maintain, thus requiring more expenditure. Charter schools also greatly outperform district schools in terms of the overall passing rate. This is primarily because, while reading scores are similar between the two types of schools, district shcools score significantly lower in math.

COMPARISON:
- When comparing the highest-performing and lowest-performing school dataframes, it is evident that the top 5 schools are charter schools with fewer than 2,283 students and a spending of no more than $637 per student. In contrast, all the bottom 5 schools are district schools wikth more than 2900 students anda  spending of over $638 per student.
- When comparing math and reding scores by grade across all schools, reading levels are similar, but math grades show significant gaps. The type summary dataframe indicates that improving math scores should be a top priority for district schools.
