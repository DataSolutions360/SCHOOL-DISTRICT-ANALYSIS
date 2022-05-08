# SCHOOL-DISTRICT-ANALYSIS
## Project Overview ##
**The purpose of this project is to analyze the data of an entire School District.  This encompases aspects of funding and student grades, to is used to learn new insights and visually provide clear results on each school's performance. Additionally, to uphold state-testing standards, this analysis was conduced twice due to potential academic dishonesty among a group of students. The implications of omitting the potentially dishonest data are also discussed.**

## Resources ##

**Resources:** All data used in this analysis can be found inside of the [Resources](https://github.com/DataSolutions360/SCHOOL-DISTRICT-ANALYSIS/tree/main/Resources) folder.

**Software:** Python 3.7, Anaconda, Gitbash, Jupyter Notebook, VS Code

## Results ##

The analysis to an audit on the scoring impact of the ninth grade students of Thomas High School.  The first time, the analysis included the full set of data, and the second analysis, all the ninth grade class of THS were omitted from overall results, to distinguish a difference of significance.

Below is a summary of the DISTRICT after omitting ninth graders' scores with NaN.

![image](https://user-images.githubusercontent.com/8845050/167273554-bfa46998-f240-4cbf-a257-c82fe92b1331.png)

  Since replacing the ninth graders' reading and math scores with NaN, the following changes int he results for Thomas High School are as follows:
  
    - Overall passing percent for Thomas High School fell to 65%
    - Overall passing percent for entire school district fell to 64.9%
    - Thomas High School fell out of the top five schools

  When the ninth graders of Thomas High School had their scores omitted from the calculations, the following changes occured:
  
    - The overall passing percentages of Thomas High School decreased by 0.11%
    - The averahe scores of Thomas High School for math and reading increased by 0.06% (little change, but not negatively impacting, 
    which is significant for this analysis)
    - School Rankings remained unchanged.  Thomas High School is still the 2nd best performing school in the district 
    with an overall passing rate of 90.6% for 10-12th graders
    
## Analysis of School Budget and School Size ##

The analyses that the average scores and passing percentages do NOT have a significant effect, with respect to spend per student.  
Cabera High School received $68 *LESS* per student as top performer, compared to John High School, which is one of the lowest performing schools.
This elludes to the point that more spend per student does *NOT* correlate to better performing scores.  
More factoral analysis is required further, if desired.  Based on high level analysis, Overall pass percent shows an INVERSE 
correlation to spend vs performance.

![image](https://user-images.githubusercontent.com/8845050/167283724-438ee1d6-4792-4435-8524-6d7648dd4a62.png)

When looking at School Size as a factor for analysis, Large Schools have the *LOWEST* average scores, as well as passing percentage.  
At this level of consideration, individual subject content(reading vs math) are not a facotr, and over passing is the sole deciding factor.
Small and Medium schools are 90 and 91%, respectively, hence negligible difference.

![image](https://user-images.githubusercontent.com/8845050/167286113-1be90818-270b-485f-b06c-904a3dbd1ab1.png)



