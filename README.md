# Module-4
PyCitySchools with Pandas

## Overview of the school district analysis

The purpose of this analysis is to gather, clean and visualize the data from the standaized tests data from a variety of schools in the district to provide insigths about performance trends and patterns in order to make decisions and have a strategic and informed point of view to improve the metrics in consideration.

## Results
* How is the district summary affected?

We can clearly aprecciate that the affected columns are % Passing Math, Reading and of course Overall passing percentage, that's do to the fact that when we eliminate 9th grades from Thomas High School we actually diminish the students who aprroved meaning there was a good amount of students coming from that set that actually passed both math and reading, this is not a rule, if the percentaje of that set was actually lower than the general mean for passing students in the other school we would have actually seen an increment in this percentajes. 
  
  ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/district_analysis_previous.png)
  
  ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/district_analysis_new.PNG)
  
  
* How is the school summary affected?

Well, since we change the grades for 9th grades with NaN instead of removing them from the analysis we actually get the same results regarding all the columns except for passing percentages, and that's just natural because for Thomas High Shcool the analysis we are performing is actually for the 10th, 11th and 12th graders for passing percentages, it wouldn't be suitable to just remove the 9th graders because other wise the data would have told us that the budget, for example, was divided in fewer students, leading to an incorrect insigth, whenever we are doing data analytics we need to consider how the maths and the statistics are affected by the data and have those considerations presentes whenever we come with a new insigth, it should always be "the observation + the conditions".  

  ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/per_school_summary_previous.png)

  ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/per_school_summary_now.PNG)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
When comparing to other schools Thomas High School is affected but in a sligth way, it would have been really different if the concentration of the other passing percentages for the other grades was too low. We see the changes in the passing percentages 

* How does replacing the ninth-grade scores affect the following:

  * Math and reading scores by grade
  
  Basically no change, since we have this scores divided by school and by grade the other schools data is not affected, obviously we see that 9th graders from thomas high school are not considered. And how we saw during this analysis the passing percentages were affected, so in the other tables we migth see a sligth change in the data set in wich this students were, meaning that for example in the by School spending table if those students aren't part of the first interval it's like nothing ever happened to that data, but let's say that those students were part of the second interval of spending rates per student, there we would have seen that the passing percentages are different and that is just beacuse we have a different universe of data in both analysis. 
  
    ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/math_scores_by_grade.PNG)  ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/reading_scores_by_grade.PNG)
    
  * Scores by school spending
  
    ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/Scores%20by%20school%20spending.PNG)
    
  * Scores by school size
  
    ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/Scores%20by%20school%20size.PNG)
    
  * Scores by school type
  
    ![alt text](https://github.com/MauricioIQA/Module-4/blob/main/Resources/Scores%20by%20school%20type.PNG)
   
 ## Summary
 
 1.- Math Passing percentage
 
 2.- Reading passing percentage
 
 3.- Overall passing percentage
 
 4.- No info about 9th graders from THS grades. 
   
