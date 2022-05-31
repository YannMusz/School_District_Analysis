# School_District_Analysis_Challenge
PyCitySchools with Pandas

## Main Objective
1. Open Jupyter Notebook files from local directories using a development environment.
2. Read an external CSV file into a DataFrame.
3. Use multiple methods to perform a function on a DataFrame.
4. Perform mathematical calculations on columns of a DataFrame or Series.


## Purpose
A school district asked for a snapshot of several key metrics. The primary analysis was centered on the performance of math and reading scores preparation for a board meeting.  After the review of the Data, it was determined that the 9th grade class was suspect of cheating and the school board asked for the data to be analyzed again for better comparison.


## PythonData Environment
1. Anaconda 
2. Conda 
3. Jupyter-Notebook 
4. ipykernal 
5. Python 
6. Pandas 
7. Numpy 
8. 
## Process
1. Open Jupyter Notebook files from local directories
2. Read an external CSV file into a DataFrame.
3. Format a DataFrame column.
4. Determine data types of row values in a DataFrame.
5. Apply the groupby() function to a DataFrame.
6. Use multiple methods to perform a function on a DataFrame.
7. Perform mathematical calculations on columns of a DataFrame or Series.

## Results

### How is the district summary affected?
Original Analysis:
![Pic 1](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_dist_sum_2_decimals.PNG)


Adjusted Analysis:
![Pic 2](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_dist_sum_2_decimals.PNG)

When comparing the two charts, removing less than 500 test scores had very little impact on the almost 40,000 student data set. 

### How is the school summary affected?

Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being too high.  After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.  

Original Analysis:
![Pic 3](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_THS_90.PNG)

Adjusted Analysis:
![Pic 4](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_THS_65.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
In the original analysis, Thomas High School ranked 2nd in the district raising suspicion wihtin the school district
Original Analysis:
![Pic 5](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_top_5_schools.PNG)

After adjustment of the 9th grade data, Thomas High School ranked in the middle

Adjusted Analysis:
![Pic 6](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_bottom_8_schools.PNG)


### Adjusted Averages using the Math and Reading Scores 

The scores have been replaced with null values and shows up in Python programming as NaN in the following charts. 

![Pic 7](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_math_by_grade_HS.PNG)
![Pic 8](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_read_by_grade_HS_correct.PNG)

### Scores by school spending

Thomas High School falls in the $630-$644/student spending range.  However, the hundredths place was needed to see the nominal changes. 

Original Analysis:
![Pic 9](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_spend_updated.PNG)

Adjusted Analysis:
![Pic 10](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_spending_updated.PNG)

There was very little  impact by changing the 9th grade scores. 

### Scores by school size
Original Analysis:
![Pic 11](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_size_updated.PNG)

Adjusted Analysis:
![Pic 12](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_size_updated.PNG)

There was very little impact by campus size due to changing the 9th grade scores. 

### Scores by school type

Original Analysis:
![Pic 13](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/1_type_updated.PNG)

Adjusted Analysis:
![Pic 14](https://github.com/YannMusz/School_District_Analysis/blob/main/Resources/2_type_updated.PNG)

There was very little impact by school type by changing the 9th grade scores. 

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed drastically

2. Thomas High School's ranking dropped from 2nd position to 8th

3. Data at the grade level will now show as "NaN" in reports for all of  the 9th grade students 

4. Campus math and reading averages and passing percentages all saw substantial shifts 

