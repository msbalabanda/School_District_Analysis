# School_District_Analysis
BACKGROUND
1) The purpose of this analysis is to help Maria find evidence of academic dihonesty for Thomas High School ninth graders by analyzing the reading and maths grade that are belived to have appear been altered. The school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. Maria has requested to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and a report to describe how these changes affected the overall analysis. We proceed analyzing the rest of the data by repeating the school district analysis from Module 4 project found in PyCitySchools.ipynb.

RESULTS
2) After replacing the reading and math scores we took a look at the district and school summary DataFrames in order to answer the following questions.

•How is the district summary affected?
School District Summary Charts

Before cleaning the data
 * Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
   79.0, 81.9, 75, 86, 65
 
 After Cleaning the data 
  * Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
    78.9, 81.9, 74, 85, 64
 Results:- There is a slight decrease in the district averages
 
 •How is the school summary affected?
 
  * Before cleaning the data:- Thomas highschool has an overall passing percentage of 90.94%
  * After cleaning the date:-  Thomas highschool has an overall passing percentage of 90.63%
 Results:-the difference when excluding the Thomas High Schools 9th grade students Reading and Math scores is slight and their % Overall Passing placement does not           change much either. 

•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  *  Replacing ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools does not affect their % Overall Passing      mark.  They are still within within the 90 percentile passing mark.
  
•	How does replacing the ninth-grade scores affect the following:
  *  Math and reading scores by grade :- Thomas High School still places second in the top five Schools in the district.

  *  Scores by school spending:- Thomas High School Spending per student increased from $638.00 to $888.53.
  
  *  Scores by school size:- There is a slight decrease in the medium(1000-2000) school size date
  
  *  Scores by school type:- There is a slight decrease in overall passing percentage in the charter school type. Whereas the overall passing percentage district        school type remains unchanged.


3) Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
  * The four changes are reflected in the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks and the funding for each student
  Each category of our analysis indicates minor differences with the exception of funding for each students which is ~ approximately $200.  Lastly, Thomas High    School still remains the 2nd top school in our dataset. Therefore based on our analysis, there is no evidence supporting academic dishonesty for this school.


