# School District Analysis Challenge

## Project Overview
The school board has requested data be analyzed for use to find trends involving the students at each of the schools in the client's school district.
Two different data sets were provided. The first data set provides the following information on the schools:
- School Name
- School Type
- School Budget

The second data set provides information about the students in the district, and provides the following information:
- Student ID
- Student Name
- Gender
- School Name
- Reading Scores
- Math Scores

The two data sets were cleaned and the following seven metrics were pulled from the information for the school board:
- District Summary  
    
![District Summary](https://user-images.githubusercontent.com/36859475/138621955-72891091-8080-435d-8fd2-e60d78b8182e.PNG)

- School Summary    
    
![School_Summary](https://user-images.githubusercontent.com/36859475/138618667-0e557027-231e-4857-8e33-3b9b76346965.PNG)

- High and low Performing Schools    
    
![High_Performing_Schools](https://user-images.githubusercontent.com/36859475/138618794-afeca1e0-fff6-46b3-a4f5-0354f3e1577c.PNG)
    
![Low_Performing_Schools](https://user-images.githubusercontent.com/36859475/138618801-c76d9e72-c0d5-4051-9740-93a0f2f3a8ba.PNG)

- Math and Reading Scores by Grade    
  1. Math Scores    
      ![Math_scores_by_grade](https://user-images.githubusercontent.com/36859475/138619604-3504093b-aceb-4c9d-a668-9cbd9fa14542.PNG)
  2. Reading Scores    
      ![Reading_scores_by_grade](https://user-images.githubusercontent.com/36859475/138619665-d2d27bd0-abda-4bea-a198-9fcd13b4b7c5.PNG)

- Scores by School Spending    
    
![Scores by School Spending](https://user-images.githubusercontent.com/36859475/138619790-7b523389-218c-4d91-9c93-23898bdda6fc.PNG)

    
- Scores by School Size    
    
![Scores_by_School_Size](https://user-images.githubusercontent.com/36859475/138619847-a53537ce-9721-43dd-9664-cd3c3b0a0f81.PNG)

- Scores by School Type
    
![Scores_by_School_type](https://user-images.githubusercontent.com/36859475/138619906-e1fe5fa6-a223-4bb7-9e34-18645f91c294.PNG)

### Evidence of Academic dishonesty
After the intital analysis it was discovered that there was academic dishonesty involving both reading and math scores from Thomas High School's Ninth Grade Class.
The scores were changed to Nan in the data frames, and the metrics above were recalculated to account for the change in data.

## Results
The district's data as seen in the data frames above provide a few insights that could be looked into.
- In this case budget per student did not seem to have any correlation as some of the lower spending schools had some of the highest passing rates. This could come down to how the money is spent rather that how much a school spends per student. More information would be neccesarry to look in to this.
- School size is one big factor in determining overall student passing percentages. This effect can be seen once total students students at a school start to exceed 2,000.
- A student that attends a charter school is much more likely to have passing averages in both Math and reading with a 36% difference in this factor.

## Summary    
- Overall the changes due to the academic dishonesty were negligible with less than a tenth of a percent overall change, decreasing in passing percentages, to the districts data. To provide further understanding as to why the score removal has so little effect on the total; there are only a total of 461 Thomas High School 9th grade scores being removed. This is out of a total of 39,170 scores that were orignally looked at before the academic dishonesty was discovered.
- Looking at the data at the school level shows a few minute changes. 
  1. A tenth of a percent decrease in the percent of students passing math at Thomas High School
  2. 3 tenths of a percent decrease in students passing reading at Thomas High School
  3. 3 tenths of a percent decrease in overall passing rate for Thomas High School
  4. The overall average in math and reading scores did decrease, but by less than a tenth of a percent.

