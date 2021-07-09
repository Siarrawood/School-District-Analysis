# School-District-Analysis
Utilizing Jupyter Notebook and Python to analyze school district data based on their budget and priorities

# Project Overview
Maria, the chief data scientist in the city school district, needs to analyze multiple forms of data across a school district to gain insight on school performance based on student funding and standardized test scores. This project's purpose is to aggregate data and showcase trends in school performance. 

# Challenge
The school district discovered the standardized test scores for the ninth graders at Thomas High School had been altered. Thus, we need to replace the math and reading scores for Thomas High SChool with NaNs while making sure the rest of the data has not changed. 

# Results
## School District Summary
### Prior to Data Removal
![](Images/Original_District_Summary.png)
### After Data Removal
![](Images/District_Summary.png)
Whem looking at average scores and passing percentages among the fifteen high schools in our dataset, the average math score dropped .1, but the average reading score remained unaffected. The three metrics of percentages of passing all decreased by approximately .1%-.3%. 

## School Summary
### Prior to Data Removal
![](Images/Original_School_Summary.png)
### After Data Removal
![](Images/School_Summary.png)
The school summary was affected greatly at first because when we just removed the data the passing percentages for reading, math, and the overall passing percentage for Thomas High School all drastically dropped from around 90% to approximately 65%. This would ultimately affect the performance relative to the other schools as Thomas High School would not be ranked in the top 5 with an overall passing rate below 70%.

However, once we recalculated our data with just the 10th-12th graders scores, the data was much less affected as shown below. Now, the school summary is nearly the same. The top five schools and bottom five schools remain unchanged, and Thomas High School remains in the top 5.
![](Images/School_Summary2.png)
![](Images/Top_Schools.png)
![](Images/Bottom_Schools.png)

# Summary
