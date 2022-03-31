# School_District_Analysis
Use Jupyter Notebook and Pandas library to perform the analysis for standardized tests for a school district review the math and readings.
We also analyze the performance of schools based on spending per student, school size and scool type to get a better idea of high performing and low performing schools.

## Analysis

### District Analysis
![image](https://user-images.githubusercontent.com/100053788/160964621-e6267597-3991-4475-9d30-255e3e03a216.png)

- A single table present the data for the number of schools in this district and the total budget. We observe that the reading scores over the 15 schools are better compared to the math scores. The overall passing percentage sits at 64.9% and can be improved.

### School Analysis
![image](https://user-images.githubusercontent.com/100053788/160965706-74cd36bf-a232-4f79-9893-f4e9733f5ee7.png)

                                                      
- **Overall Performance** - This provides a detailed analysis of each school's perfromance. We can see that having a higher budget does not necessarily guarantee a better performance. All low performing schools are District type and High Performing schools are Charter Type.

![image](https://user-images.githubusercontent.com/100053788/160966488-66f2ab90-e83b-443e-91eb-69e4d9c55059.png)


- **Low Performing Schools** - The 5 lowest performing schools have per capita spend of over 600$. It can also be argued that greater number of students can drive down the overall average scores but this issue still needs to be addressed on a deeper level, with a more detailed analysis.

![image](https://user-images.githubusercontent.com/100053788/160966989-6005de00-8f06-48dd-ba76-c22344056e6b.png)

- **High Performing Schools** - The only noticeable trend is that the these schools are charter type. The size, budget and per student spend varies over the 5 schools.

### Thomas High School

![image](https://user-images.githubusercontent.com/100053788/160968385-b5193992-0f2d-4ac8-8213-df99d908ba1d.png)      

- **Before Removing 9th Grade Scores** - Theomas High School is one of the lowest performing schools in the district with an overall passing percentage of 65.7%

![image](https://user-images.githubusercontent.com/100053788/160968767-296d871f-f216-4fea-bb98-1f4f93d539d1.png)

- **After Removing 9th Grade Scores** - Thomas High School becomes 2nd best school in the district in terms of overall performance. This suggests that the issue with this school lies in the performance of 9th Grade Students.

- **Average Grade** - Thomas High School 9th Scores display NaN Value
- **School Spending** - No Change
- **School Size** - % Overall Passing Changes by 0.01% mid size schools
- **School Type**  Average Scores and % passing increase by 0.01% for Charter School Type

### Summary
![image](https://user-images.githubusercontent.com/100053788/160969928-0166ad52-5f36-4119-b1ee-4fccb710ac73.png)      ![image](https://user-images.githubusercontent.com/100053788/160969973-f900f2dc-0696-4bda-b77a-c089f7d49a2e.png)


- **Average Math and Reading Scores per Grade** - 9th grade scores for Thomas High School show NaN.

- **School Performance** - Thomas High School becomes the 2nd best performing schools based on overall passing percentage, which changes from 65.07& to 95.63%.

- **Value of % Passing in Math** - Value for % passing in math changes from 66.91% to 93.18%.

- **Value of % Passing in Reading** - Value of % passing in reading changes from 69.66% to 97.02%



