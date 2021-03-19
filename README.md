# School_District_Analysis
* Module 4 - Pandas, Anaconda and Jupyter

# Overview of the school district analysis: Explain the purpose of this analysis.
* We have assisted Maria with preparing and analysing student math and reading scores in order to determine school performance and assist in making decisions on school funding. We completed one set of analysis on the data, however, the school board alerted Maria and her supervisor that the data in the dataset (students_complete.csv) contains invalid data. This was caused by the reading and math grades for 9th graders at Thomas High School being altered, and are thus considered invalid. Due to this invalid data, we have been asked to repeat our analysis by replacing the invalid data and repeating our analysis.

# Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## How is the district summary affected?
![District Summary Comparison] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Resources/District%20Summary%20Comparison.PNG
* All of the average scores and % passing has decreased by a small amount/% (i.e. tenth of a decimal) when comparing the data before the 9th grade data was removed versus after it was removed. The change on average is only a ~ -0.19% change in the values.

## How is the school summary affected?
![School Summary Comparison] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Resources/School%20Summary%20Comparison.png
* We can see that the average scores and % passing has decreased by a small amount/% (i.e. tenth of a decimal) when comparing the data before the 9th grade data was removed versus after it was removed. The only score that increased is the average reading scores. On average, there is a ~ - 0.15% change in the values.

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
![Relative Performance Comparison] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Resources/Relative%20Performance%20Comparison.PNG
* By changing one line of code, we are able to sort the schools ranking based on each of the average scores and % passing. The only rankings that changed for Thomas High School was their average math scores where they dropped from 4th to 5th, and their % passing reading which dropped from 1st to 3rd.

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
![Scores by Grade] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Resources/Scores%20by%20Grade.png
* Since the only change that was done is the grade 9 data at Thomas being removed, there is no impact on the other grades for this specific analysis. The grade 9 data now shows nan as the initial values were replaced/removed. 

### Scores by school spending
![Scores by School Spending] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Resources/Spending%20Summary%20Comparison.png
* Thomas High School was in the $630 - $644 range and only caused a small amount/% decrease (i.e. hundredth of a decimal) when comparing the data before the 9th grade data was removed to after they were removed. The only score that increased is the average reading score where the change was also very small (i.e. hundredth of a decimal). On average there is a ~ -0.05% change in the values.
### Scores by school size
![Scores by School Size] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Resources/School%20Size%20Comparison.png
* Thomas High School is a medium size high school. Again the change is a small amount/% decrease (i.e. hundredth of a decimal) when comparing the data before the 9th grade data was removed to after they were removed. The only score that increased is the average reading score where the change was also very small (i.e. hundredth of a decimal). On average there is a ~ -0.03% change in the values.

### Scores by school type
![Scores by School Type] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Resources/School%20Type%20Comparison.png
* Thomas High School is a 'charter" school type. Again the change is a small amount/% decrease (i.e. hundredth of a decimal) when comparing the data before the 9th grade data was removed to after they were removed. On average there is a ~ -0.02% change in the values.

# Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
* The grade 9 data being removed seemed to have a very small impact on the data. Depending on which data/analysis we are looking at, the average change ranges from only -0.02% to -0.19%, which is insignificant as it only changes the data by a tenth of a decimal at most.
* The only change that was 'significant' is their rankings, where their % passing reading dropped from rank 1 to rank 3.
* The other significant change is that since the grade 9 data was replaced with nan at Thomas High School, we do have data for that grade to compare against other grades if we wanted to do an analysis involving grade.
* With regard to the code itself, there were also few changes that needed to be made, other than to change the count of the number of students to reflect that the grade 9 student data for Thomas High School was removed.


# Appendix 
* [Pre-Adjustment Analysis] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/Pre-Adjustment%20Analysis.ipynb
* [Post-Adjustment Analysis] https://github.com/BBBrian1124/School_District_Analysis/blob/Challenge/Challenge/PyCitySchools_Challenge.ipynb
* [Repository Link] https://github.com/BBBrian1124/School_District_Analysis/tree/Challenge
