# School_District_Analysis
Module 4 Using Pandas and Jupyter Notebook

## Project Overview
Using Pandas and Jupeter Notebook, replace incorrect data in columns using various logical operations and create a new analysis of school district performance.

1. Replace the ninth-grade math and reading scores from Thomas High School.
2. Keep all other dataassociated with the ninth-grade students and Thomas High School intact.
    Filter DataFrames using logical operators.
    Replace the incorrect values with NaN.
    Explain how pyCitySchools analysis changes after handling with the incorrect data.
    
## Resources
- Data Source: schools_complete.csv and students_complete.csv
- Software: Python 3.6.1, Jupyter Notebook

## Summary (includes challenge summary)
The analysis of the PyCitySchools data show that:
 - original PycitySchools district summary  vs revised PycitySchools district summary as below:
    - PyCity scores - Average Math score - 79.0 and Average Reading score - 81.9 
    - Revised scores - Average Math score - 78.9 and Average Reading score - 81.9
 - original PycitySchools school summary vs revised PycitySchools School summary as below:
    - Removing 9th grade thomas high school students does not affect numbers when it is calculated for each individual schools data.
 
 - Recalculate High and low performing schools data:
    - PyCity scores - Average math scores range from 83.06 to 83.8, Reading scores range 83.9 to 84.04
    - Revised scores - Average math scores range from 83.06 to 83.6, Reading scores range 83.9 to 83.95
    
    For bottom performing schools 
    - PyCity scores - Average math scores range from 76.84 to 77.07, Reading scores range 80.74 to 80.96
    - Revised scores - Average math scores range from 76.84 to 77.07, Reading scores range 80.74 to 80.96
    
 - Recalculate scores by grade, scores by school spending, scores by school size and scores by school type.
 
    - by grade -Not affected - for other grades - except 9th grade from Thomas high school removed
               
    - by spending -  remains same for both data
                  
    - by size - PyCity scores
                   - Small : Average Math score - 83.8 and Average Reading score - 83.9
                   - Medium : Average Math score - 83.4 and Average Reading score - 94
                   - Large : Average Math score - 77.7 and Average Reading score - 81.3
              - Revised scores
                   - Small : Average Math score - 83.8 and Average Reading score - 83.9
                   - Medium : Average Math score - 83.4 and Average Reading score - 94
                   - Large : Average Math score - 77.7 and Average Reading score - 81.3
    - by type - PyCity scores
                  For charter type : Average Math score - 83.5 and Average Reading score - 83.9
                  For district type: Average Math score - 77.0 and Average Reading score - 81.0
              - Revised scores
                  For charter type : Average Math score - 83.5 and Average Reading score - 83.9
                  For district type: Average Math score - 77.0 and Average Reading score - 81.0
 


