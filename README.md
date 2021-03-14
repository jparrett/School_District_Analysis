# School District Analysis
Module 4:  Pandas and Jupyter Notebook

## Overview of Project
The purpose of this project is to agregate school and student data.   This information will be presented to the school board to provide them with insight on performance trends and patterns in regards to budget and standardized test scores.   The school board will use the information provided to make strategic decisions at the school and district level in regards to student funding, school budgets and priorities.   

## Results: 

By refractoring the code, the code was able to execute significantly faster.  

### 2017:  

Original code ran in:  1.1797 seconds and the refractored code ran in:  0.1953 seconds.
  <img src="/Resources/VBA_Original_2017.png" width="600"> [VBA_Original_2017.png](/Resources/VBA_Original_2017.png)
  
  <img src="/Resources/VBA_Challenge_2017.png" width="600"> [VBA_Challenge_2017.png](/Resources/VBA_Challenge_2017.png)


### 2018:  

Original code ran in:  1.1875 seconds and the refractored code ran in:  0.2227 seconds.
  <img src="/Resources/VBA_Original_2018.png" width="600"> [VBA_Original_2018.png](/Resources/VBA_Original_2018.png)
  
  <img src="/Resources/VBA_Challenge_2018.png" width="600"> [VBA_Challenge_2018.png](/Resources/VBA_Challenge_2018.png)

### Comparison of the Code
- The original code consisted of nested `for` statements to run through the data. 
  <img src="/Resources/OriginalCode.png" width="600"> [OriginalCode.png](/Resources/OriginalCode.png)   


- For the refractored code, a stock ticker index array was utilized.    This led to a cleaner and more efficient run of the data.
  <img src="/Resources/RefractorCode.png" width="600"> [RefractorCode.png](/Resources/RefractorCode.png)




## Summary: 
- What are the advantages or disadvantages of refactoring code?
  - The advantages of refractoring code is that the code is more efficient and written cleaner.
  - The disadvantages of refractoring code is that the code can be more complicated to read and more comments are necessary to document the steps.

- How do these pros and cons apply to refactoring the original VBA script?
  - The refractored code was significantly quicker at processing the data.   
  - The ability to write an array based on the ticker index variable was more difficult to understand and took more time to write.    
