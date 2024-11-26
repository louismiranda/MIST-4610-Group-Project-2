# Mist 4610 Group Project 2
## GROUP 1: NYPD Arrests Dataset

## Team Name: 
4610Fa24Group1

## Team Members:

1. Louis Miranda [@louismiranda](https://github.com/louismiranda)
2. Bond Surber [@bondsurber](https://www.github.com/bondsurber)
3. Sidd Kawatra [@siddKawatra](https://github.com/siddKawatra)

## Description of dataset:

Our dataset is a historical record of all the New York Police Department's (NYPD) arrests made from 2006-2023. We obtained our dataset through this website given to us by Dr. Srinivasan: [https://catalog.data.gov/dataset]. Our dataset is composed of 19 columns consisting of more than 5 million rows of data (approx. 5,725,522 rows) that vary in terms of data types. It details the type of offense committed (Dangerous Drugs, Assault,...), the level of the offense committed (Felony, Misdemeanor,...), the borough of the arrest (Brooklyn, Manhattan,...), and the perpetrator's age group (<18, 18-24,...) and gender (M, F, U) which are all of data type 'String'. It also details the date of the arrest, including the month, day, and year, which is of data type 'Date & Time'. Additionally, the arrest key is recorded which is of data type 'Number(Whole)' and the location of the arrest is listed in terms of longitude and latitude which are both of data type 'Number(Decimal)'. A screenshot of our dataset in .xls format can be seen below, in which the columns highlighted in gold are the dimensions used in our project. Overall, this dataset has a variation of different dimensions that help us dive deeper into the arrests and crimes that occurred in New York City (NYC). 


<img width="1440" alt="Screenshot 2024-11-25 at 12 28 53 PM" src="https://github.com/user-attachments/assets/829a2a45-d649-4e31-ad6c-58bcdac70eb8">


## Question 1:

Question: Which demographic factors, specifically age or gender, are most strongly associated with certain types of offenses?

Importance: 

This question is important because it allows one to understand how demographics come into play when NYPD are making arrests, and allow one to identify the relationships between age, gender, and type of offense committed, as well as explore the patterns associated with their relationships. This allows one to answer questions like "Are younger individuals more involved in specific types of offenses, like theft, compared to older groups?", which can pinpoint which age groups and gender are most high-risk for theft or other types of offenses. Furthermore, this question can reveal underlying systemic behavioral problems that tend to develop during earlier ages and continue to develop as they get older, which could be the root cause for some of the broader crime challenges that New York City faces. By answering this question, everyone in the New York City community, from the NYPD and policymakers to the people, can collaborate together to build targeted intervention programs that can prevent a certain demographic group from committing the crime they're most associated with in the first place, or stop them from repeating the offense again as they grow older. Additionally, this question helps to build trust between the people and the police by providing better transparency in what types of people are being arrested, ensuring any potential bias or inequalities in arrests is openly identified and addressed.  


<img width="1440" alt="Screenshot 2024-11-25 at 2 53 06 PM" src="https://github.com/user-attachments/assets/153b3396-4667-4d9a-84a8-c37da31df7cb">
<img width="438" alt="Screenshot 2024-11-25 at 3 40 40 PM" src="https://github.com/user-attachments/assets/922d6802-0347-4a27-85b1-3ff2b006d8a8">


In this visualization, we created a heatmap to illustrate the percentage of arrests that make up a certain type of offense based on age group and gender; in other words, how likely are arrests for a specific crime to be made up by a certain age group and gender. We were able to identify that Males in the 25-44 age group were consistently the majority of arrests across all types of offenses, showing that this demographic group is the most high-risk overall. Furthermore, out of the total number of arrests for the offense "Cannabis Related Offenses", 28.29% were Males ages 18-24 and 51.07% were Males ages 25-44, marking almost a 2x jump in between the demographic groups; this is also the same case for arrests of "Dangerous Drugs" where Males in 18-24 made up 24.53% and jumped significantly to 38.34% for Males in 25-44. This shows that NYC Males who are arrested for cannabis and other drugs at an early age are more than likely to repeat the same offense again when they are older, revealing that drug-related habits that exhibit in early ages tend to continue and attribute to drug-related offenses later down the line. This information can be a huge benefit to NYPD as they can build more drug awareness campaigns to prevent the early onset of drug addiction among the youth and create substance-abuse rehabilitation programs or drug courts to focus more on helping older people get clean and recover from their addiction, instead of incarcertions. We continued to analyze this same data in our next visualization.


<img width="1440" alt="Screenshot 2024-11-25 at 3 31 57 PM" src="https://github.com/user-attachments/assets/3770348d-2eac-4ead-a1df-199cf2047d4e">
<img width="435" alt="Screenshot 2024-11-25 at 3 41 15 PM" src="https://github.com/user-attachments/assets/e6535a71-fdd3-4562-a8bd-a2e1bcf6d3f1">


In this visualization, we created the same heatmap, but examined the percentage of arrests that make up a certain age group and gender going down all types of offenses, instead; in other words, how likely a certain age group and gender are to be arrested for a specific offense compared to all other offenses. This visualization allowed us to further our claim that NYC has prominent drug problems within their communities as we were able to see that all age groups and genders made up a significant portion of arrests for "Dangerous Drugs" compared to all the other types of offenses down the list. Moreover, we were able to gain deeper insights as to what types of offenses are females most likely to be arrested for. We found that Females in all age groups make up a significant proportion of arrests for "Assault 3 & Related Offenses" and "Petit Larceny", showing that these are the types of crimes NYC Females are most likely to be involved in throughout their lifetime. Using this information, the NYPD and the broader NYC community can build more youth programs, like youth camps and mentorships, aimed towards correcting adolescent behaviors that may lead towards potential arrests, especially stealing that is common among young women. 

## Question 2:

Question: Which boroughs are likely to see an increase/decrease in arrests over the next 6 years?

Importance: 

This question is important because it enables the police to be aware of the general trendline of crime or where crime is headed in NYC up until 2030. With this information, the NYPD can effectively allocate their resources, from officers and patrol units to crime prevention programs, to boroughs that might see a bigger increase in arrests than others. Boroughs whose arrests are expected to increase could receive additional personnel and increased surveillance, whereas boroughs whose arrests are expected to decrease could have their budgets and staff optimized to ensure that resources are not being wasted in areas with expected low crime. Additionally, 

This question is important because it enables the police and public to be aware of the districts that are most likely to have drug violations occur as well as the most popular times for drug violations to occur. With this information, the police department could deploy more officers to districts that are more likely to have drug violations as well as during peak hours likely for drug violations. It is more effective to deploy more officers during peak hours to efficiently utilize their services and economically be more worthwhile. Additionally, the public would feel safer if they know more extensive measures are being taken to keep them safe during peak hours in popular districts for drug violations. The second question builds on the last question’s revelations that district A1 has the most drug violations occurring between 14-22 hours (2 PM - 10 PM). From this insight, it is important to find the streets within district A1 that are most likely to have drug violations occur on. This would further help the police department to target streets to keep officers on during 14-22 hours. Additionally, the public would be more informed of what streets to avoid during 14-22 hours to be safer and further away from any possible drug violations. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 42 PM" src="https://user-images.githubusercontent.com/128402101/235008200-aa0fd1c7-8407-4eec-8faf-7e8458dc66f3.png">

In analyzing the count of drug violations by district and hour of day, we found that there is a peak in the trend line of most districts between the 14th and 22nd hour of the 24 hour period. This indicates that across virtually all districts, drug offenses spike between 2:00 pm and 10:00 pm, and the district with the most drug offenses during this time is district A1. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 50 PM" src="https://user-images.githubusercontent.com/128402101/235008216-fd327af8-4b38-4e01-8d4d-7dca8255246f.png">

After delving deeper into this finding, we found that of the streets in district A1 between the times of 2:00 pm and 10:00 pm, the street with the most drug violations is Boylston Street- with Washington, Tremont, and Beach streets trailing behind it. Thus, an appropriate course of action would be to increase police presence on Boylson St, Tremont St, and Beach St between 2:00 pm and 10:00 pm These findings are important and useful in that they can help law enforcement narrow down in which areas and during what times they should patrol more often or dispatch more units to, to help eradicate drug-related crime. Without this analysis, law enforcement may be wasting resources by patrolling the wrong areas or patrolling areas during times drug offenses are not even likely to occur. Utilization of these findings would improve the efficiency and effectiveness of law enforcement.

## Manupulations applied to the data set for analysis:

We did not have to manipulate any data, but we did have to standardize the data set. A standardized data set focuses on transforming raw data into usable information before it's analyzed. Our data fits that description as we have quantifiable data that can be measured and adheres to the standard of being meaningful, interpretable data. Our data also has no duplicate data, irrelevant data, redundant data, inaccurate data, or low-quality data. We also have cleansed the data, ridding it of any incomplete, irrelevant, or inaccurate data. On top of all of this, we have formatted our data and it contains no 3rd party imports.

## Tableau packaged workbook

The packaged workbook containing the visualizations shown above is attached to this repository.
