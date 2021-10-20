# PyCitySchools_Challenge with Python

## Overview of Project

### Purpose
Originally I helped Maria and her supervisor create DataFrames using python which would organize a students and schools excel sheet which contained lots of information. Now the school board has notified us that there has been some academic dishonesty for reading and math test scores for Thomas High School 9th graders. We have had to update the dataframes to show 'NaN' for these testing scores for Thomas High School 9th graders to better uphold testing standards. We then had to redo the analysis and find how these changes affected it. **Please note: Pictures in this analysis are not labeled and will be in Original then Altered code picture following**

## Results
- **How is the district summary affected?**
	 After taking a look at the district summary, we can see that any changes were very minimal. 
	 [![District Original](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/District%20Summary%20original.png "District Original")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/District%20Summary%20original.png "District Original")
	 [![District Summary Changed](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/District%20Summary%20changed.png "District Summary Changed")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/District%20Summary%20changed.png "District Summary Changed")
- **How is the school summary affected?**
	 Thomas High School had a passing rate of 90.94%, once the 9th graders were removed from the data set the overall passing rate dropped by 30% which was a very big change.
	 [![School Summary Original](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Summary%20Original.png "School Summary Original")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Summary%20Original.png "School Summary Original")
	 [![School Summary Changed](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Summary%20Changed.png "School Summary Changed")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Summary%20Changed.png "School Summary Changed")
- **How does replacing the ninth graders math and reading scores affect Thomas High Schools performance relative to the other schools?**
	 Originally Thomas High School was ranked near the top with overall passing rate, however after removing the 9th grade testing score, they dropped hard towards the middle of the group. 
	 [![Thomas Performance Original](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Performance%20Original.png "Thomas Performance Original")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Performance%20Original.png "Thomas Performance Original")
	 [![Thomas Performance Changed](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Performance%20Changed.png "Thomas Performance Changed")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Performance%20Changed.png "Thomas Performance Changed")
- **How does replacing the ninth-grade scores affect the following?**
	- Math and reading scores by grade
	 The change here is that the scores now show NaN instead of the normal grades.
	- Scores by school spending
	 There was a very minimal change that happens here, having to look in the hundreths to see any sort of difference.
	 [![Spending Original](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/Spending%20Original.png "Spending Original")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/Spending%20Original.png "Spending Original")
	 [![Spending Changed](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/Spending%20Changed.png "Spending Changed")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/Spending%20Changed.png "Spending Changed")
	- Scores by school size 
	 Once again there was very minimal change that is negligible.
	 [![Size Original](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Size%20Original.png "Size Original")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Size%20Original.png "Size Original")
	 [![Size Changed](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Size%20Changed.png "Size Changed")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Size%20Changed.png "Size Changed")
	- Scores by school type
	 Once again barely any change here, any change was very minimal.
	 [![type original](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Type%20Original.png "type original")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Type%20Original.png "type original")
	 [![Type Changed](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Type%20Changed.png "Type Changed")](https://raw.githubusercontent.com/HadiAli08/School_District_Analysis/main/Resources/Images/School%20Type%20Changed.png "Type Changed")
## Summary
Removing the 9th graders scores did have a fairly big impact on the data that we had. First, Thomas High Schools passing rate dropped dramatically from 91% to 65%. Secondly the 9th graders scores no longer show, and instead have been replaced with NaN so that they are no longer counted. Third, Thomas High School has dropped in ranking very harshly from 2nd to the middle of the schools. Lastly, all of the scores did change, whether minimally or harshly they are all different. 
