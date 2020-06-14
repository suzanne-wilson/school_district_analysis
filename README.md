# school_district_analysis
# Module 4 Challenge
### Thomas HS is a medium-sized charter school that spends $638 per-capita.  An issue was discovered with the calculation of math and reading scores for the ninth graders at Thomas, and the district decided to remove those scores from district-level summary statistics.  

### After setting to missing the math and reading scores for the Thomas High School ninth graders, impacts on other analyses were noted. The following changes were observed:

### District level changes
### 	• District-level average math score declined by 0.1, from 79.0 to 78.9
### 	• The district-level math, reading, and overall passing percentages declined by 1% 
	
### 	School level changes
### 	At the school level, only Thomas High School was impacted, with the following changes:
###   	• Minimal change to the average math score, and no change in the average reading score
###   	• A decline in Thomas High School's math, reading, and overall passing percentages of about 26 percentage points
###   	• The percent of students passing math dropped from 93.3% to 69.7%
###   	• The percent of students passing reading dropped from 97.3% to 66.9%
###   	• The percent of students passing overall dropped from 90.9% to 65.1%
	
### Within-district ranking changes
### Thomas HS ranking relative to other schools in the district dropped.  Thomas was ranked second of the 15 schools in the district based on the percent of students passing both math and reading (90.9%).  The decline in this measure resulted in Thomas HS dropping to a rank of 13 of 15.   

### Subgroup score changes 

### For ninth graders in the district, the average math score changed from 78.9 to 78.7, and the average reading score changed from 81.9 to 81.8.  All other grades' average scores did not change.

### The average math and reading scores by school spending, school size, and school type did not change.

### Conclusion
### The method used to calculate the passing percentages at each school took the ninth-grade Thomas HS students' scores out of the numerators, but not out of the denominators.   This impacted the school's passing percentages and its ranking within the district.  A recommendation for next steps on this project would be as follows:
###   	• Recalculate the school-level summaries with an appropriate method that does not count missing values as failures
###   	• Merge these school-level summary statistics with the student-level data, and recalculate mean scores and passing percentages using student-level data.
