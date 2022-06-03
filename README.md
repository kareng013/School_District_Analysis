# School District Analysis

## Overview 

The purpose of this analysis is to rexamine the school district data for results due to academic dishonesty. We will be replacing a few students math and reading results from Thomas High School with NaNs and redoing the school district analysis to evaluate the difference between the new data and old data. 


## Results

### How is the district summary affected?

The District Summary as displayed in Images 1 and 2 below has the following differences between the two data sets:
- Average math score decreased by 0.1 for total students
- Average reading score remained the same at 81.9
- The percentage of students passing math decreased by 0.2%
- The percentage of students passing reading decreased by 0.1%
- Overall passing rate went down by 0.3%

![Old_District](https://github.com/kareng013/School_District_Analysis/blob/main/Old%20District%20Summary.png)

**Image 1: Old District Summary**

![New_District](https://github.com/kareng013/School_District_Analysis/blob/main/New%20District%20Summary.png)

**Image 2: New District Summary**

This data set shows there was not a huge difference once the old data was nulled. However, it also shows that a few students did not pass due to academic dishonesty.

### How is the school summary affected?

In this section we look at the school summary by evaluating the 10th-12th graders final scores for Thomas High School specifically. After removing the 9th graders scores there appears to be a slight difference in the data results as displayed in Images 3 and 4. 

- Average Math score decreased by by 0.06
- Average Reading score increased by 0.05
- Average % for both Reading and Math declined
- Overall passing percentage declined to 90.63%

![Old_Summary](https://github.com/kareng013/School_District_Analysis/blob/main/Old%20School%20Summary.png)

**Image 3: Old School Summmary**

![New_Summary](https://github.com/kareng013/School_District_Analysis/blob/main/New%20School%20Summary.png)

**Image 4: New School Summary**


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School performs relatively well, despite the academic dishonesty, compared to the other top performing schools. Thomas High remains as the second best performing school overall. Analyzing the data, Thomas High School did lose a few % points in both reading and math, falling below Griffin High School. 

![Top_Schools_Old](https://github.com/kareng013/School_District_Analysis/blob/main/Old%20Top%205%20Schools.png)

**Image 5: Previous Top 5 Performing Schools**

![Top_Schools_New](https://github.com/kareng013/School_District_Analysis/blob/main/New%20Top%205%20Schools.png)

**Image 6: New Top 5 Performing Schools**

### How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade

Comparing the new resuls below with the old, it's visible that 

By removing the math and reading scores from the 9th grade at Thomas High School, overall there is not a comparible change due to the similar scores across all schools from grades 9-12. 

![Old_Scores](https://github.com/kareng013/School_District_Analysis/blob/main/Original%20Scores.png)

**Image 7: Original Math(left) and Reading(Right) Scores**

![Math_Score](https://github.com/kareng013/School_District_Analysis/blob/main/New%20Scores.png)

**Image 8: New Math(left) and Reading(Right) Scores**


### Scores by school spending

As displayed in the school spending below in Image 9, there was no relative changes in the scores affected by school spending. This means school spending had no affect on the results of a students score.

![School_Spending](https://github.com/kareng013/School_District_Analysis/blob/main/School%20Spending.png)

**Image 9: School Spending**

### Scores by school size

Image 10 displays the school size, and as seen below it can be seen that schools with small and medium size saw a higher passing rate as opposed to Large schools that had a passing rate of 58%.

![School_Size](https://github.com/kareng013/School_District_Analysis/blob/main/School%20Size.png)

**Image 10: School Size**

### Scores by school type

Scores by school type shows that District schools had a much lower passing rate as opposed to Charter school types. There was no changes made from the previous analysis.

![School_Type](https://github.com/kareng013/School_District_Analysis/blob/main/Scores%20School%20Type.png)

**Image 11: Scores by School Type**


## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- Image 12 below shows that only 2 students scores were replaced showing there was not much of a difference in the overall results

![Student_results](https://github.com/kareng013/School_District_Analysis/blob/main/Student%20results.png)

**Image 12: Student Results**

- Overall scores by % only changed by 0.3%

- Math Score % went down overall by 0.2%, not a significant change

- Reading Score % went down overall by 0.1%, not a significant change
