# pandas-challenge

In this challenge, we are looking at the city's district-wide standardized test results. Within the district, there are 15 schools with a total of 39,170 students. 7 of the schools are district schools and the other 8 are charter schools. The charter schools have 12,194 students which is significantly less than the district schools which have 26,976 students. This is a summary of the district as a whole and by each school:

![district_summary](https://github.com/otybaasandorj/pandas-challenge/blob/main/Images/district_summary.png)

![per_school_summary](https://github.com/otybaasandorj/pandas-challenge/blob/main/Images/per_school_summary.png)

Charter schools have a higher percentage of overall students passing both math and reading with a score of 70 or higher. Charter schools have 90.43% whereas district schools have 53.67%. We see charter schools have a higher average math score, average reading score, percentage passing math, percentage passing reading, and the percentage overall passing. 

![school_type_summary](https://github.com/otybaasandorj/pandas-challenge/blob/main/Images/school_type_summary.png)

When analyzing the highest and bottom performing schools by the percentage of overall students passing both math and reading with a score of 70 or higher, top 5 of the highest schools were all charter schools. The bottom 5 were all district schools.

![highest_performing](https://github.com/otybaasandorj/pandas-challenge/blob/main/Images/highest_performing.png)
![bottom_performing](https://github.com/otybaasandorj/pandas-challenge/blob/main/Images/bottom_performing.png)

There is a correlation between the school size and standardized test scores as the smaller (<1000) and medium (1000-2000) size schools scored higher than the large (2000-5000) size schools. The highest performing students also fell in the <$585 range when analyzing the spending summary which may suggest that spending more/ budgeting more per student does not result in higher test scores in math and reading.

![size_summary](https://github.com/otybaasandorj/pandas-challenge/blob/main/Images/size_summary.png)
![spending_summary](https://github.com/otybaasandorj/pandas-challenge/blob/main/Images/spending_summary.png)
