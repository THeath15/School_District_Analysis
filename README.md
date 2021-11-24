# School District Analysis
In this module,  we are tasked  to help Maria, the Chief Data Scientist of the City School district analyze data on student funding and Student Standardize Test Scores. The task assigned is to aggregate the data and showcase school trends and performance. This project analysis will assist the school board and Superintendents in making decisions regarding school budget and priorities.
## Project Overview
After the intial module anaylysis has been submitted .The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has assigned a task to to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.
 
## Resources
Pandas & Numpy libraries Jupyter Notebook (PythonData environment created using Python 3.10 and Anaconda)
csv’s provided: schools_complete.csv, students_complete.csv
PythonData Environment:
 - Anaconda version 1.7.2
 - Conda ver. 4.9.0
 - Jupyter-Notebook version Python 63
 -ipykernal version 7.22
 - Python 3.7.10
 -Pandas 1.2.4
 - Numpy  1.20.1
 -GitBash version 2.28.0.windows.1

## School District Analysis  Results


# District Summary Data Frame
The after adjustment of turning  9th graders at Thomas High School into turned null data and resulted the the  testing data of 461 which recalculated the percentages of passing math, passing reading, and the overall passing. The total count of students did not change as that was run on the count of the student ids, which was not turned into null data.
The percentage of students passing math, reading, and both (overall) is reduced by 1%.
##![District Summary DataFrame](https://user-images.githubusercontent.com/92903447/143296702-4aa97a14-14a3-4c41-8036-d58af293ef4e.png)

# School Summary Dataframe after adjustment
![School Summary Dataframe after Adjustments](https://user-images.githubusercontent.com/92903447/143296761-01345138-793d-4eef-9bfb-ad8a83c186ee.png)


# High and Low Performing Schools

![Top 5 Performing Schools](https://user-images.githubusercontent.com/92903447/143296978-4c1955cc-8189-4761-9379-d8372d95e51d.png)

![Low Performing Schools](https://user-images.githubusercontent.com/92903447/143297133-f6b97119-ac2a-4603-b920-f1bb3e90eb4d.png)


#**#Average Math and Reading Scores**
![Average math scores](https://user-images.githubusercontent.com/92903447/143297371-c51439ad-fe4f-4729-8eb5-a7074820af63.png)

![Average reading scores](https://user-images.githubusercontent.com/92903447/143297454-dae38022-037e-4ea3-a38b-830ecc2cf814.png)

#**Scores by School Size and School Types**
![Scores by school size](https://user-images.githubusercontent.com/92903447/143297510-dc972e9c-3d5c-40d0-a3a6-92114cdfd437.png)

![Scores by School Type](https://user-images.githubusercontent.com/92903447/143297522-46557f6a-79eb-4dbf-b097-9d0e71d49dcc.png)

#**##Budget spending summary per Student**
![Spending summary per student](https://user-images.githubusercontent.com/92903447/143297590-7bc2ba0e-86f2-4cc7-a7e5-0929cefba36d.png)


## School District Analysis Summary

For the 9th grade at Thomas Hight School, data will now shos as "NaN" value
The overall passing rate for Thomas High School changed dramatically from  to 65%. to 91%


