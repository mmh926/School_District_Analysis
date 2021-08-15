# School_District_Analysis ReadMe
By: Monica M. Holmes
3/17/2021

![image](https://user-images.githubusercontent.com/78371845/129494527-2de32f4c-4fef-49db-94f5-6681d8e36bdb.png)
![image](https://user-images.githubusercontent.com/78371845/129494530-4da01e7c-f62d-4c05-8ab7-beb06f60f257.png)



# PyCitySchools District Analysis Report

## OVERVIEW OF THE SCHOOL DISTRICT ANALYSIS:


## •	The purpose of this analysis 
  o	The purpose of this analysis is for me to help Maria, chief data scientist for a city school district, with preparing all standardized test data for analysis, reporting, and presentations. The analysis will provide insight into performance trends and patterns which are used to inform discussions and strategic decisions regarding budgets and priorities at school and district levels. I will help analyze data to showcase trends on students’ performance, student funding, and students standardized test scores. Access to every student’s math and reading scores and the schools they attend will be provided to me. 
  
  o	In addition, Maria and I were tasked with making comparisons with the original data results, and data with one school’s data, Thomas High School, being omitted. 















# •	Results:
## •	How is the district summary affected?
  o	 The district summary Data Frame (DF) shows for the two outputs, there was a 0.2 decrease in the revised Percentage Passing Math score, a 0.1 decrease in the revised Percent Passing Reading results, and 0.3 decrease in overall change in Percent Overall Passing results.  From a district standpoint, the 3 tenths of a percent decrease in % Overall passing grades is not indicative of fraud in Thomas high School (see District Summary screen prints below).

  o	District summary DF - original:
 
![image](https://user-images.githubusercontent.com/78371845/129494783-3aa24805-6aa5-47d1-8569-df1b97da88d5.png)



  o	District summary DF - revised:
 
![image](https://user-images.githubusercontent.com/78371845/129494785-ef417ba8-4271-4694-bd36-67dd76850a95.png)


## •	How is the school summary affected?
   o	With respect to the school summary, and how the removal of the Thomas High School data affects the results, the DF’s show no difference in the Per_School_Summary_DF reports. Cabrera High School had the highest % Overall Passing score, with 91.334769 percentile (see Per_School_Summary_DF screen print below).  



   o	Per_School_Summary_DF – Original :
 ![image](https://user-images.githubusercontent.com/78371845/129494809-e9b832b5-2e5c-455f-94ee-818a63226afd.png)




   o	Per_School_Summary_DF – revised:
 ![image](https://user-images.githubusercontent.com/78371845/129494813-1d743415-3d16-4c0d-b32a-7ab04a6818f7.png)





## •	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   o	There was a decrease of 0.317688 percent in Thomas High Schools the top five highest performing schools report after replacing the ninth graders’ math and reading scores. There was no change relative to other schools (see screen prints below). 

   o	Top 5 highest-performing schools - original:
   
 ![image](https://user-images.githubusercontent.com/78371845/129494831-7b74f22d-93d7-41b6-98e8-226e553288ad.png)


   o	Top 5 highest-performing schools - revised:
 
![image](https://user-images.githubusercontent.com/78371845/129494834-0dd573a0-671d-4508-b80d-05163ec4d57c.png)



## •	How does replacing the ninth-grade scores affect the following?
   o	Math and reading scores by grade:
   
     	Replacing the ninth-grade scores only affected the math scores by grade for Thomas High School by reducing the percentage score accordingly.  No other school or grade was affected (see Math Scores by Grade screen prints below). 
     
   o	Math scores by grade - original:
   
   ![image](https://user-images.githubusercontent.com/78371845/129494869-39a17d01-d9f4-4cb6-8543-85ec4dfcedf0.png)

 
   o	Math scores by grade - revised:
   
   ![image](https://user-images.githubusercontent.com/78371845/129494874-f8a03812-4094-43ed-9cb7-a661593d6e4d.png)
  
 
     	Similarly, replacing the ninth-grade scores did not affect schools the reading scores by grade, except for Thomas High School’s, 9th grade score (see Reading Scores by Grade screen prints below).  
     
   o	Reading scores by grade - original:
   
   ![image](https://user-images.githubusercontent.com/78371845/129494897-39403cf7-0092-4b88-87c8-dee25b45ad1d.png)

 
   o	Reading scores by grade - revised:
   
   ![image](https://user-images.githubusercontent.com/78371845/129494904-d51f80bd-52dc-4e6d-a977-e9598737b45c.png)


 
## •	Scores by school spending:
   o	Replacing the ninth-grade scores affected the $630 -$644 spending range (per student) scores and percentages as follows (screen prints to follow):
   
    	The Average Math Score decreased by 0.016853 percent.
    	The Average Reading Score increased by 0.011788 percent.
    	The %Passing Math decreased by 0.02162 percent.
    	The %Passing Reading decreased by 0.072532 percent.
    	The %Overall Passing decreased by 0.079423 percent.

   o	Spending summary df - original:
   
   ![image](https://user-images.githubusercontent.com/78371845/129494942-ed728e30-64ee-4a5b-94cf-f1fa9353ba8e.png)

   
 
   o	Spending summary df - revised:
   
   ![image](https://user-images.githubusercontent.com/78371845/129494955-a7b43626-4c59-4c9c-99d5-4aa7451ba732.png)

 




## •	Scores by school size:
   o	Replacing the ninth-grade scores affected the scores by school size, like the way it affected school spending (screen prints to follow):
   
    	The Average Math Score decreased by 0.013483 percent.
    	The Average Reading Score increased by 0.009431 percent.
    	The %Passing Math decreased by 0.017297 percent.
    	The %Passing Reading decreased by 0.058026 percent.
    	The %Overall Passing decreased by 0.063538 percent.
    
   o	These changes conclude, that after the revision made to the ninth-grade scores, the medium sized schools decreased in % Overall Passing by less than one percent, which is a score of 70 or above.

   o	School size summary - Original:
   ![image](https://user-images.githubusercontent.com/78371845/129494986-2ada198d-0cb5-40e1-a431-0f2cca4f1412.png)

   
 
   o	School size summary - revised:
  ![image](https://user-images.githubusercontent.com/78371845/129494987-7efc7298-8ad8-4908-a713-81489a4f5aff.png)






   o	Scores by school type:
   
    	Replacing the ninth-grade scores did not affect the scores by school type to the tenth percent. However, if the decimal percentage by were expanded, differences may show, however, the differences were not greater than one percent (Scores by School Type screen prints, below). 
    
   o	Scores by school type - original:
   
   ![image](https://user-images.githubusercontent.com/78371845/129495009-b7fda551-5fc0-47e4-ae3f-b9ea7529ee3e.png)

 
   o	Scores by school type - revised:
   
   ![image](https://user-images.githubusercontent.com/78371845/129495012-c9831283-09ad-43f4-8dbd-22a52b588b79.png)

 














# •	Summary:

o	In summary, the District Summary report showed a decrease of 3 tenths of a percent in % Overall passing grades. 

After reviewing reports where Thomas High School’s 9th grade math and reading scores were removed, there were little to no changes to report. In particular, the math and reading Scores by Grade reports showed only the 9th grade score for Thomas High School was affected. The removal of grades did not affect other schools’ math and reading scores. In contrast, only the $630 -$644 spending range (per student) scores and percentages showed the changes decreased one to two hundredth of a percent in all reported scores (and 0.079423 %Overall Passing), and only the Average Reading Score, increased, which was only 0.011788 percent. The Scores by School Size report showed similar affects as School Spending, only the medium sized schools decreased in % Overall Passing by, which was less than one percent, (the score is based off scores of 70 or above). Lastly, there were no changes to the tenth percent to report from analyzing Scores by School Type reports. However, if the decimal percentage by were expanded, differences may visualize, but, the differences would not amount to one percent or greater.

To conclude, there were increases and decreases in the math and reading data as a result of the removal of Thomas High School ninth-grade scores, however, the changes are all less than one percent and the same fluctuation occurred at the district level. There does not appear to be any fraudulent activity present.

