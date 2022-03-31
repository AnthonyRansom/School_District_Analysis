# School_District_Analysis

## Overview of Project

### Purpose
The School board has requested an analysis of the Math and Reading scores of various schools in the district.
This analysis will look at the Math and Reading scores of each school in the district in order to provide insight into trends of the passing grades compared to budget allocation and school sizes.

The analysis will provide insight into the following areas:
 - The average Math and Reading scores compared to School size
 - The average Math and Reading scores compared to school spending
 - The average Math and Reading scores compared to the types of schools within the district
 
Due to unforeseen circumstances it has been requested by the School board to exclude the Math and Reading scores of the 9th Grade students of Thomas High School within this analysis.
This analysis will look further at how excluding the 9th grade student data from Thomas High has affected the overall district results.

## Results
The analysis of the Math and Reading scores for the various schools within the district was completed using both the original dataset and the excluded data requested by the school board.
The below provides insight into how the exclusion of the relevant data has affected the school and district passing results:

 - The exclusion of the 9th grade results from Thomas high had very little affect on the district results with a very minor difference of less than 1% change in the average scores and pass rates
	- The below screenshots show the change in the average math score and the passing rates showed a slight decrease of less than 1% but the average Reading scores has stayed the same
	#### District Results - Original Data
	![School District Results - Original Dataset](/analysis/School_District_Results_-_Original_Dataset.PNG)
	#### District Results - Adjusted Data
	![School District Results - adjusted Dataset](/analysis/School_District_Results_-_adjusted_data.PNG)

 - Overall the exclusion of the 9th grade results of Thomas high did not affect any of the other schools results as expected but the following was observed:
	- The below shows the per school analysis before the data was adjusted to exclude the 9th grade results of Thomas High
	![School_Summary_-_original_dataset](/analysis/School_Summary_-_original_dataset.PNG)
	
	- After the Thomas High Math and reading score were set to "NaN" the Average Math and Reading scores and passing rates had a large 25-30% decrease for Thomas High:
	![School_Summary_-_adjusted_data](/analysis/School_Summary_-_adjusted_data.PNG)
	
	- Due to the above it was concluded the 9th grade students from Thomas High should be excluded from the total student count as including a large amount of students with no grades resulted in too many outliers which skewed the results. 
	The analysis was adjusted to excluded the 9th grade students from the Thomas High student count and only include the 10th, 11th and 12th grade students which shows the Math, Reading and Overall passing rates increase only indicating about 1% difference
	compared to the original data.
	![School_Summary_-_Thomas_high_9th_grade_excluded](/analysis/School_Summary_-_Thomas_high_9th_grade_excluded.PNG)
 
 - Thomas high maintained a spot as one of the top 5 schools in the district before and after the adjustment of the 9th grade data
	#### Top Schools - Original Data
	![top_performaing_schools_-_orginal_dataset](/analysis/top_performaing_schools_-_orginal_dataset.PNG)
	#### Top Schools - Adjusted Data
	![top_performaing_schools_-_Thomas_high_9th_grade_excluded](/analysis/top_performaing_schools_-_Thomas_high_9th_grade_excluded.PNG)
	
	#### Bottom Schools - Original Data
	![Bottom_performaing_schools_-_orginal_dataset](/analysis/Bottom_performaing_schools_-_orginal_dataset.PNG)
	#### Bottom Schools - Adjusted Data
	![Bottom_performaing_schools_-_orginal_dataset](/analysis/Bottom_performaing_schools_-_Thomas_high_9th_grade_excluded.PNG)


 - Replacing the 9th grade marks for Thomas high had little affect overall on the district analysis once the 9th grade scores were removed from that analysis:
	- The alteration of the data only affected the Grade 9 results for Thomas High while the other grades at Thomas High and other schools were not affected
	#### Math Scores by Grade - Orginal Data vs adjusted Data
	![Math_scores_by_grade_-_original_data](/analysis/Math_scores_by_grade_-_original_data.PNG) ![Math_scores_by_grade_-_adjusted_data](/analysis/Math_scores_by_grade_-_adjusted_data.PNG)
	#### Reading Scores by Grade - Orginal Data vs adjusted Data
	![Reading_scores_by_grade_-_original_data](/analysis/Reading_scores_by_grade_-_original_data.PNG) ![Reading_scores_by_grade_-_adjusted_data](/analysis/Reading_scores_by_grade_-_adjusted_data.PNG)
	- The Scores by school spending showed no decrease or increase in any of the score or pass rates within the various brackets
	#### Scores by School Spending - Orgiinal Data
	![scores_school_spending_original_data](/analysis/scores_school_spending_original_data.PNG)
	#### Scores by School Spending - Adjusted Data
	![scores_school_spending_adjusted_data](/analysis/scores_school_spending_adjusted_data.PNG)
	- The Scores by school size showed no decrease or increase in any of the average scores or pass rates within the various school size brackets
	#### Scores by School Size - Orgiinal Data
	![scores_school_size_original_data](/analysis/scores_school_size_original_data.PNG)
	#### Scores by School Size - Adjusted Data
	![scores_school_size_adjusted_data](/analysis/scores_school_size_adjusted_data.PNG)
	- The Scores by school type showed no decrease or increase in any of the average scores or pass rates for the Charter and District school types
	#### Scores by School Type - Orgiinal Data
	![scores_school_type_original_data](/analysis/scores_school_type_original_data.PNG)
	#### Scores by School Type - Adjusted Data
	![scores_school_type_adjusted_data](/analysis/scores_school_type_adjusted_data.PNG)

## Summary

The requested alteration to the 9th grade Math and Reading scores did not show any major differences to the overall district results but there are some minor differences that can be noted:
 - The average Math score for the district had a 0.1% decrease 
 - The percent passing rate for Math shows a decrease by 0.2%
 - The percent passing rate for Reading shows a decrease by 0.3%
 - The overall passing percent shows a decrease of 0.1%
 
From the above results reported by the analysis it can be concluded that the reported dishonest data for the 9th grade students at Thomas high did not affect the overall district or school results in any significant way.
