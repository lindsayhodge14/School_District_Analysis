# School_District_Analysis
#### Learning Pandas

## Overview of Project
The purpose of this analysis was to create a summative data frame that would allow for data to be compared between unadjusted school data and data that excluded freshmen scores at Thomas High School while also considering the schools' different sizes, types, and budgets.

## Results
* How is the district summary affected?

<![ChallengeDistrictSummary.png]>(Resources/ChallengeDistrictSummary.png)

<![ModuleDistrictSummary.png]>(Resources/ModuleDistrictSummary.png)

The changes created by excluding freshmen scores at THS were the percentage of students passing math decreased by .1 %, the percentage of students passing reading increased by .1 %, and the percentage passing overall declined by roughly .2 %.

* How is the school summary affected?

<![ChallengePerSchoolSummary.png]>(Resources/ChallengePerSchoolSummary.png)

<![ModulePerSchoolSummary.png]>(Resources/ModulePerSchoolSummary.png)

There were no evident changes in the per school summary that can be seen in the screenshots of the dataframes' head; however, alterations were made for THS and are noted in the following bullit.

* How does the ninth graders' math and reading scores affect THS' performance relative to other schools. 

<![ChallengeTopSchools.png]>(Resources/ChallengeTopSchools.png

<![ModuleTopSchools.png]>(Resources/ModuleTopSchools.png)

Some noteable changes were that the average math score decreased slightly, in addition to the percent passing math. The average reading score increased, but the percentage passing still slightly declined. Therefore, in total, the overall passing percentage did decrease slightly;but, it did not increase enough to move THS to a ranking different than second in the district.

* How does replacing the ninth graders' score affect the following?

  * Math and reading scores by grade
 
<![ChallengeGradeScores.png]>(Resources/ChallengeGradeScores.png)

<![ModuleGradeScores.png]>(Resources/ModuleGradeScores.png)

Similar to the district summary, screenshots do not illustrate the only changes made to the data, those being associated with THS.

  * Scores by school spending
 
<![ChallengeSpending.png]>(Resources/ChallengeSpending.png)

<![ModuleSpending.png]>(Resources/ModuleSpending.png)

As can be seen in the images, the dataframes are identical for spending. This shows that alterations made to THS data had very little impact on the districts' performance overall, as it relates to different levels of funding. 

  * Scores by school size

<![ChallengeSize.png]>(Resources/ChallengeSize.png)

<![ModuleSize.png]>(Resources/ModuleSize.png)

As can be seen in the images, the dataframes are identical for spending. This shows that alterations made to THS data had very little impact on the districts' performance overall, as it relates to different levels of funding.

  *Scores by school type

<![ChallengeType.png]>(Resources/ChallengeType.png)

<![ModuleType.png]>(Resources/ModuleType.png)

As can be seen in the images, the dataframes are identical for spending. This shows that alterations made to THS data had very little impact on the districts' performance overall, as it relates to different levels of funding.

## Summary

After reviewing all of the results produced by replacing the reading and math scores for Thomas High School's ninth graders with Nan, four key changes are present in the updated data. First, the percentage of students passing math at THS decrease due to a slight decrease in the average math score. The percentage ofstudents passing reading at THS increased, but it still resulted in a slight decrease in the percentage of students passing reading. Collectively, the decrease in THS's tests led to a lower overall passing percentage. While this did alter their statistical data in comparison to the other schools, they remained second in the district for performance.  
