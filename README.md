# Project3 - Data Visualization Track
## Education Funding Analysis

### Team Members: 
- James Draper
- Kelsey Kraft
- Mariah McLelan
- Amarilli Novel
- Hisako Yamanaka

  
### Project Overview:
Questions to Answear: How does the funding allocated to education impact the success of students and schools?

The project aims to analyze the impact of education funding on the success of students and schools. 
Specifically, the study will focus on the relationship between state funding in Texas education, SAT/ACT scores, and dropout rates. 
Through statistical and visual analysis, we will determine whether higher funding leads to better outcomes or if there is a point where the impact of funding levels off.

### Data Sets Source:
https://tea.texas.gov/

> https://tea.texas.gov/reports-and-data/school-data/campus-and-district-type-data-search

> https://tea.texas.gov/reports-and-data/school-performance/accountability-research/c[…]-graduation-and-dropout/completion-graduation-and-dropout-data

> https://tea.texas.gov/reports-and-data/school-performance/accountability-research/ap/ib-and-sat/act

> https://tea.texas.gov/finance-and-grants/state-funding/state-funding-reports-and-data

> https://tea.texas.gov/finance-and-grants/state-funding/state-funding-reports-and-data/peims-financial-standard-reports

https://schools.texastribune.org/states/tx/

### How to interact with the project

### Ethical data considerations


### Development
Began our study by searching for suitable datasets, focusing on the Texas Education system and referring to the TEA Texas Education Agency website.
We found six relevant Excel files, which we converted to .csv files. Also, we found Public Schools Explorer website, which we scraped data fpr all the districts

Our first challenge was to clean the data frames. 
We focused solely on total operating revenue, which Texas uses to support educational operations and facility construction in public school districts. 
This revenue comes from local, state, and federal funding sources, with the majority coming from state and local sources and only a relatively small amount from the federal government.  

State government aid is the primary funding source for elementary and secondary education, followed by local contributions (primarily property taxes). On average, 8% of revenues come from the federal government, 47% from the state, and 45% from local sources[^bignote2].
[^bignote2]:  McFarland, J., Hussar, B., Wang, X., Zhang, J., Wang, K., Rathbun, A., … Bullock Mann, F. (2018). The condition of education 2018. National Center for Education Statistics.

We selected "All Students" as the group for SAT and ACT scores, as other groups had inconsistent data. 
Then, we merged the SAT and ACT scores with the cleaned finance data frame and formatted and sorted the values. 
We then proceeded to conduct a **statistical analysis** of the data.


### Takeaways and conclusions:

- As expected, there is a positive correlation between total operating revenue and student count.
  That means the more students a school district has, the bigger the funding received.
  
- The budget doesn't significantly affect scores, as some schools with smaller budgets scored the highest.
  Moreover, smaller schools tend to have higher ACT and SAT scores.
  
- There is a substantial decline in academic scores when the school population increases.

- When analyzing the five largest cities in Texas by population, we discovered that Austin ISD performs the best in both SAT and ACT while having a smaller budget than Fort Worth, Dallas, and Houston.

- There is a negative correlation between Total Operating Revenue and ACT Composite and SAT Total scores, as indicated by the values of -0.03 and -0.09, respectively.

- Smaller schools, on average, do better than larger schools.

- Large Cities and large school districts have the highest dropout rates without outliers, having an upper fence of 6.1 percent.

In conclusion, education funding does not impact students' success in SAT and ACT scores. 
Also, the budget does not help with dropout rates since some schools with higher total operating revenue have the highest dropout rates.

After analyzing the data, a pertinent question arises: What is the key to success for smaller schools with higher ACT and SAT scores?

As per the American Federation of Teachers Texas, teachers must maintain an average of 20 students per class across the district, although no prescribed limit exists for individual secondary classrooms. The 22:1 ratio only applies to students in Kindergarten through fourth grade.

Further investigation may lead us to hypothesize that the optimal student-to-teacher ratio in smaller schools may be a factor that contributes to their superior academic performance when compared to larger schools with a lower percentage of teachers per student. 

To answer this question, we need to research more and this query could already be the draft of our project 2. 

