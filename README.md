# School_District_Analysis

## Overview
The school board is seeking a new, similar analysis after finding some of the data from a previous analysis on the math and reading scores was inaccurate. Seeking first to have the inaccurate data taken out of the analysis, the school board would like the analysis to be run again and to more accurately understand how the school districts and charters fared individually and overall. The school district would like the analysis to include the following: 

## Results

- A high-level snapshot of the district's key metrics, presented in a table format

![district_summary_df.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/district_summary_df.jpg)

> The previous analysis included the same number of schools, students, budget amount, average math score, and average reading score.
> The previous analysis showed different numbers for the Percent Passing: Math (75%), Reading (86%), and Overall (65%).

- An overview of the key metrics for each school, presented in a table format

![overview_by_school.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/overview_by_school.jpg)

> The previous analysis showed the following differences for Thomas High School: Average Math Score (83.418349), Average Reading Score (83.848930), Percent Passing Math (93.272171%), Percent Passing Reading (97.308869%), and Percent Overall Passing (90.948012%).

- Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  
  ![top_5_schools.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/top_5_schools.jpg)
  
  ![bottom_5_schools.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/bottom_5_schools.jpg)
  
  > Previously, Thomas High School was listed in the second position of the top schools table.
  
  - The average math score received by students in each grade level at each school
  
  ![math_scores_by_school.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/math_scores_by_school.jpg)
  
  > Average math score for Thomas High School: 9th grade was previously 83.6.
  
  - The average reading score received by students in each grade level at each school
  
  ![reading_scores_by_school.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/reading_scores_by_school.jpg)
  
  > Average reading score for Thomas High School: 9th grade was previously 83.7.
  
  - School performance based on the budget per student
  
  ![scores_by_budget.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/scores_by_budget.jpg)
  
  > The Spending Range of **$630-644 Per Student** is the only area which, excluding math and reading scores, is different in the previous analysis. Previously, the percents for the following areas were such: Passing Math (73%), Passing Reading (84%), and Overall Passing (63%).
  
  - School performance based on the school size 
  
  ![scores_by_size.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/scores_by_size.jpg)
  
  > The **Medium** School Size is the area which, excluding math and reading scores, is different in the previous analysis. Previously, the percents for the following areas were such: Passing Math (94%), Passing Reading (97%), and Overall Passing (91%).
  
  - School performance based on the type of school
  
  ![scores_by_type.jpg](https://github.com/tarajarell/School_District_Analysis/blob/master/Resources/scores_by_type.jpg)
  
  > The **Charter** School Type is the only area which, excluding math and reading scores, is different in the previous analysis. Previously, the percents for the following areas were such: Passing Math (94%), Passing Reading (97%), and Overall Passing (90%).

## Summary
While there were slight changes in the overall look at the school board's numbers, there were the most changes noted between the previous and current analysis when looking at tables by school (Thomas High), amount per student ($630-644), size (Medium), and type (Charter). 

The four major changes in the school district analysis after taking out the inaccurate data are:
1. Thomas High School's passing percentages by school are now less than previously assessed by 26.360856% for Math, 27.64526% for Reading, and 25.871559% overall.
2. The Spending Range Per Student of $630-644's passing percentages are now less than previously assessed by 6% for Math, 7% for Reading, and 7% overall.
3. The Medium School Size's passing percentages are now less than previously assessed by 6% for Math, 6% for Reading, and 6% overall.
4. The Charter School Type's passing percentages are now less than previously assessed by 4% for Math, 4% for Reading, and 3% overall.

Additionally, the top 5 schools have changed with the removal of Thomas High and inclusion of Wright High in the final spot. The tables across school by grade were also unable to report numbers for Thomas High when they previously did have the (corrupted) data included.
