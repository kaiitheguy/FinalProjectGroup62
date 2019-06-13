# STUDENT ALCOHOL CONSUMPTION

UCSD COGS108 FA19 Final Project

## TEAM NAME: 

Team Alcohol Free(Group62)

## TEAM MEMBERS: 

* Shu Yao Wu(A13579395) 
* James Beighley(A13103167) 
* Yikai Chen(A13531003)
* Falak Hotchandani(A15711717) 
* Katherine Ngo(A14530341)

## DATA SCIENCE QUESTION(S) & HYPOTHESIS: 

The specific question we are trying to solve in this project is how can we reduce the amount of alcohol consumption amongst high school students? Our data set gives us information about not only about the amount of alcohol a student consumes on weekdays and weekends, but it also includes a lot of background information on the students, like their family financial status, parent’s occupation, grades, and amount of free time they have. This project will narrow down the data by focusing on trying to find a correlation between student alcohol consumption and whether a student participates in extracurricular activities. 

Our hypothesis is that student alcohol consumption is correlated with extracurricular activities and that if a student does participate in extracurricular activities, their alcohol consumption will be relatively less than their counterparts. This is due to the assumption that if a student is busy with extracurriculars, they will have less time to consume alcohol.

## BACKGROUND:

Unhealthy alcohol use among students is a major public health concern. Although there are already many research reports(Reference 1 and 3) showing the level of alcohol consumption among undergraduate students, the research on the alcohol consumption level of high school students is still almost blank. The aim of the current research is to describe drinking patterns of US high school students along with their family backgrounds. From doing background research, we identified several common leads and motives in teenager alcohol usage(References 4 and 5). From those studies, we found that family backgrounds, including parents marriage status, parents degree, parents financial status and etc, is a crucial attributive cause in teenager alcohol usage. So we decided to research the correlation between alcohol usage and family backgrounds. We also learned how to better measure alcohol consumption(Reference 2) so that we could relate alcohol consumption better with usage and have a better understanding of the dataset(Reference 6) we are using. 

References (include links):
* Changes in undergraduate student alcohol consumption as they progress through university https://bmcpublichealth.biomedcentral.com/articles/10.1186/1471-2458-8-163
* Measuring Alcohol Consumption in the United States https://link.springer.com/chapter/10.1007/978-1-4899-1669-3_3
* College Student Alcohol Consumption, Day of the Week, and Class Schedule https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1530-0277.2007.00402.x
* Examining the role of drinking motives in college student alcohol use and problems. https://psycnet.apa.org/record/2003-04910-004
* The burden of alcohol use: Excessive alcohol consumption and related consequences among college students. https://psycnet.apa.org/record/2014-07285-012
* Student Alcohol Consumption https://www.kaggle.com/marcdeveaux/student-alcohol-consumption/data?fbclid=IwAR3hHE1tr1PkaKMKZDplvOV5fQ4xL-Lwj0s75quYg3zeY61T0qEnDvDTJvo

In conclusion, the correlation we want to find out should be lined along with the age of students. Using the dataset in Reference 6, we could get data of level of student alcohol consumption, students’ age, and their family background information.


## ETHICAL CONSIDERATIONS: 
An ethical issue we need to consider for our project is privacy. We are exploring a topic that not only reveals that the number of students who perform underage drinking but also forces us to analyze their personal background. The dataset we are using contains a lot of personal information about each student, such as their sex, age, address, family size, parental cohabitation status, parent’s education level, parent’s jobs, the reason they chose to attend their school, guardian, travel time from home to school, study time, number of failed classes, whether they receive extra educational support, whether they receive family education support, whether they take extra paid classes, extracurricular classes, and whether they attended nursery school. Although these data sets consists of a lot of data about each student’s personal background, we justified the use of this dataset because a majority of the information provided to us is binary or numerical, which means that we do not have access to the details of these aspects of their lives. For example, we do not actually have access to their specific addresses. Instead, we only know if they live in a rural or urban area. The information we will analyze is very general and privacy is not entirely a huge issue in this case. However, we will continue to acknowledge how this information is still private to some extent as we work on our project.


## DATA: 
* Dataset Name: Student Alcohol Consumption
* Link to the dataset: https://www.kaggle.com/uciml/student-alcohol-consumption?fbclid=IwAR2_MlaQXajzt3m9nxq5EPlHWKr8E66t6HuUoq5aAyoD5lgYU2JIy9p2rSo
* Number of observations: 1044


## TEAM EXPECTATIONS 
We expect each group member to be respectful and considerate of one another. We expect each team member to complete their assigned tasks to the best of their abilities, and to ask for help from other members if they are having difficulty. We expect everyone to attend our weekly meetings, and in the event that they do miss a meeting, they must be diligent in making up anything they have missed and knowing what was assigned during the meeting. We expect all members to be active in the dialogue and the direction of the team, and to be active and engaging with their teammates.
		

## Conclusion & Discussion
### Analysis result
Based on our data analysis and visulization, we conclude that alcohol consumption is definitly related to the chool performance. We define the school performance with multiple factors. We use study time, whether a student was attending extra paid classes, the number of classes a student failed, whether a student wanted to pursue higher education, school absences, and final grades of students to define their level of school involvement. We assumed that the higher the level of school involvement, the more time the student would be spending in school. After analyzing all the factors seperated with alcohol consumption level, we found that school absences and final grades has the highest level of correlation to alcohol consumption. All the other factors seems to have a weak correlation with alcohol consumption by itself.

When we combined all the school involvement factors together into one major factor, we were able to find a positive correlation between spending time with school related activities and alcohol consumption, proving our hypothesis. Therefore we conclude that individual school related factors do not make a big difference in the level of consumption of a student. We have to look at the overall school involvement of a student to predict their level of alcohol consumption.

### Limitation
Some limitations we have in our data set is that there is not a lot of detail on the alcohol consumption of the student. It is represented by levels instead of actual amounts of alcohol. Students may have very different definitions on what is considered a little alcohol and what is considered a lot, so the data may not be very accurate. We also have limitations in the size of dataset because the data is coming from a very specific area. In this case, it is students who are enrolled in math and Portuguese class. Our analysis could be stronger if this survey was given to all high school students in America.

Though our focus of the project is high school students, it is due to the limitation of our data being only on high school students. Underaged drinking can include students in middle school and even elementary school. With extra data, we may be able to analyze drinking patterns in underaged children in general.

### Future plan
In the future, we want to include more data from high shcool and university students because based on our referrence and background research, university alcohol comsumption is much more harsher than students in the high school. We believe that our analysis may be a good start to investigating a larger topic and can lead to changing the school system. If there is more proven data on how participating in extracurricular school activities, having more classes, and a higher level of school involvement as a whole can lower the alochol consumption in underaged teens, the public should support expanding afterschool activities and putting more funding into extracurriculars to keep students busy. That can provide children with safer and better environments to grow up in, leading to the betterment of other aspects of their lives. Implementing these programs would not only help the children but can also help the community. If there were more programs for students to volunteer, hold internships, participate in STEAM projects or more, that could also better the community as a whole.
