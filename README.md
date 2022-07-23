# School_District_Analysis

# Overview
The purpose of this analysis is to reanalyze standardized test score data following the relevation of cheating amongst ninth graders at Thomas High School. The Math and Reading test scores in this cohort were removed from the data set before reanalyzing. In this project, the following seven metrics are analyzed for the school district: 
1. Top 5 Peforming Schools
2. Bottom 5 Performing Schools
3. Average math score for each grade level at each school
4. Average Reading score for each grade level at each school
5. School performance based on budget per student
6. School performance based on school size
7. School performance based on school type

The findings of this analysis is then compared to the original analysis that was performed prior to the removal of suspected cheating data. 

# Results
Several key metrics were analyzed in this project. The results for each of these metrics following the removal of the 9th grade test scored at Thomas High School are displayed in tables below, alongside the results from the original analysis.

## Top 5 Peforming Schools
![image](https://user-images.githubusercontent.com/105028515/180625430-45e5a13b-21b2-4864-b34c-804165b594b4.png)


## Bottom 5 Performing Schools
![image](https://user-images.githubusercontent.com/105028515/180625446-0fcf78eb-5379-4603-863b-0e49fbca8916.png)

## Average math score for each grade level at each school
![image](https://user-images.githubusercontent.com/105028515/180625590-f4a8ff8d-d398-41a8-8c9c-4fb1d1258b16.png)

## Average Reading score for each grade level at each school
![image](https://user-images.githubusercontent.com/105028515/180625600-20d57718-6ddb-40ba-930f-fc72c3fb74fa.png)

## School performance based on budget per student
![image](https://user-images.githubusercontent.com/105028515/180625820-b959ee78-9743-4c2c-b183-4a52677a32d8.png)

## School performance based on school size
![image](https://user-images.githubusercontent.com/105028515/180625839-15728237-5679-4f77-b20e-af0666953c3a.png)

## School performance based on school type
![image](https://user-images.githubusercontent.com/105028515/180625854-78345dfa-5ef1-4eb0-b7f2-72997812e5bf.png)

# Summary
There are a few changes to the school district analysis report that we see after replacing the reading and math scores of the ninth graders at Thomas High School. The overall performance for Thomas High School slightly decreased when removing the ninth grade test scores. However, this decrease was minimal and did not affect their ranking amongst other schools in the district - Thomas High School still ranked #2. Passing percentage for Thomas Highschool plummited greatly once these scores were replaced with NaN (from about 91% to 65%), but this was to be expected. As such, these scores were ommited when calculating the overall passing rate for the school. It is also worth noting that the ninth graders at Thomas High School performed very well in math and reading in the original analysis of their scores by grade, especially compared to othere schools in the district. Once their grades were removed, however, we are no longer able to compare their performance to other schools.
2.
