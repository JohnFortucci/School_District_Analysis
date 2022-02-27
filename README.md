# School_District_Analysis

## Introduction

The purpose of the analysis is to modify the data from the original analysis to eliminate the values for Thomas High School's 9th grade math and reading scores. A new analysis will be created that does not include the eliminated values. 

With the values of the new analysis , we will review both sets of data to understand the impact the modified data has on the results.

## Results

### Confirm data has been correctly modified

We have been asked to eliminate the math and reading score for Thomas High School's 9th grade. To do this we will replace the math and reading score with a NaN values. 

The tables below show a summary snapshot of the data :- 
- Before the data is modified 
- After the data has been modified.

#### Data summary before the data is modified
![Summary count before change](/Resources/Summary_before.png)

![THS Summary before change](/Resources/Summary_before_THS.png)

#### Data summary after the data is modified
![Summary count after change](/Resources/Summary_after.png)

![THS Summary after change](/Resources/Summary_after_THS.png)

From the above we can see that the summary of the school data before any modifications to the data set :- 
- Counts for both math and reading scores is 39170.
- There are no NaN values in the data set.
- There are 461 entries for math and reading for Thomas High School 9th Grade

After the data set was modified , we can see that :-

- Counts for both math and reading scores is 38709.
- There are 461 NaN values .
- There are no entries for math and reading for Thomas High School 9th Grade
- There are 461 NaN values for math and reading for Thomas High School 9th Grade

From the above we can conclude that the data has been modified correctly.

#### Impact on district Summary

Comparing the original district summary below
![District sumamry original](/Resources/District_summary_original.png)

To the modfied district summary with the data set modified to remove 9th grade Thomas High School maths and reading scores below.
![District sumamry original](/Resources/District_summary_modified.png)

It can be seen that there is a minimal movement in some of the summary data.
- Average math score decreased by 0.1
- Percentage passing maths decresed by 0.2%
- Perecentage passing reading decreased by .01%
- Percentage overall passing decreased by 0.3%

#### Impact on school Summary

From the image below it can be see that the only impact to the school summary if to the school where the 9th grade results are eliminated (Thomas High School).
![School summary comparison](/Resources/School_summary_comparison.png)

If we look into the results if Thomas High School the change is minimal , it should be noted that when you include that 9th grade students in the calculations , the change is significant , but when you only include 10th ,11th and 12th grade students the changes are minimal. The comparison below is based on comparing with calculations that do not include 9th grade student counts.

##### Original data set
![School summary THS orginal](/Resources/School_summary_THS_orginal.png)

##### Modified data set
![School summary THS modified](/Resources/School_summary_THS_modified.png)

It can be seen that there is a minimal movement in some of the summary data.
- Average math score decreased by approximately 0.06
- Average math score increase by approximately 0.05
- Percentage passing maths decresed by approximately 0.1%
- Perecentage passing reading decreased by 0.3%
- Percentage overall passing decreased by 0.3%

#### New comparison and impact relative to other schools

![Top 5 Comparison](/Resources/Top_5_comparison.PNG)

Based on the above comparison , there is no impact relative to the other schools. Thomas High School remained in the same position

#### Maths and Reading Scores by grade

There is no significant impact on the Maths and Reading score by grade , other than 9th grade for Thomas HIgh School has no value.

#### Impact on scores by school spending

This is no significant impact , when the output is rounded to 1 decimal place , you can only see a slight difference when you go to 2 decimal places.

##### Original
![Spending_original](/Resources/Spending_original.png)

##### Modified
![Spending_modified](/Resources/Spending_modified.png)
#### Impact on scores by school size

This is no significant impact , when the output is rounded to 1 decimal place , you can only see a slight difference when you go to 2 decimal places.

##### Original
![Size_original](/Resources/Size_original.png)

##### Modified
![Size_modified](/Resources/Size_modified.png)

#### Impact on scores by school type

This is no significant impact , when the output is rounded to 1 decimal place , you can only see a slight difference when you go to 2 decimal places.

##### Original
![Type_original](/Resources/Type_original.png)

##### Modified
![Type_modified](/Resources/Type_modified.png)


## Summary

There is no significant change in the school district analysis with the removal of 9th Grade math and reading for Thomas High School. Changes are only significant when you include the student count of the 9th grade for Thomas High School. But based on the instructions when had to elimiante these.

The following can be concluded :- 

- Thomas High School average and percentages had minimal change 
- The overall school district results changes are minimal , average math sore decreased by less than 0.1 , perecentage passing maths , reading and overall passing decreased slightly.
 
