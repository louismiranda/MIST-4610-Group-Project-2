# Mist 4610 Group Project 2
## GROUP 1: NYPD Arrests Dataset

## Team Name: 
4610Fa24Group1

## Team Members:

1. Louis Miranda [@louismiranda](https://github.com/louismiranda)
2. Bond Surber [@bondsurber](https://www.github.com/bondsurber)
3. Sidd Kawatra [@siddKawatra](https://github.com/siddKawatra)

## Description of dataset:

Our dataset is a historical record of all the New York Police Department's (NYPD) arrests made from 2006-2023. We obtained our dataset through this website given to us by Dr. Srinivasan: [https://catalog.data.gov/dataset]. Our dataset is composed of 19 columns consisting of more than 5 million rows of data (approx. 5,725,522 rows) that vary in terms of data types. It details the type of offense committed (Dangerous Drugs, Assault,...), the level of the offense committed (Felony, Misdemeanor,...), the borough of the arrest (Brooklyn, Manhattan,...), and the perpetrator's age group (<18, 18-24,...) and gender (M, F, U) which are all of data type 'String'. It also details the date of the arrest, including the month, day, and year, which is of data type 'Date & Time'. Additionally, the arrest key is recorded which is of data type 'Number(Whole)' and the location of the arrest is listed in terms of longitude and latitude which are both of data type 'Number(Decimal)'. A screenshot of our dataset in .xls format can be seen below, in which the columns highlighted in gold are the dimensions used in our project. Overall, this dataset has a variation of different dimensions that help us dive deeper into the arrests and crimes that occurred in New York City. 


## Question 1:

Question: In Boston, what days of the week tend to have more drug violations? For those days of the week that experience more drug violations, what times during the year do those same days experience most of their drug violations?

Importance: 

This question is interesting because it allows one to understand on what days of the week there are more drug violations. One can then understand trends by answering this part of the question, such as “More drug violations occur on weekends or weekdays,” or, “Certain days have a very low amount of drug violations or some have a  very high amount.” This can help the police in understanding what days to look out for people committing this crime. The second part of the question breaks down whether or not drug violations vary within Boston during the year. This allows one to understand how different months and seasons can impact the drug use within Boston. Some trends that can build from this question revolve around how Boston police respond to spikes in drug use throughout the year. This relates to the data because the dataset contains information amongst all crimes throughout all of Boston’s history in recent years.  

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 16 PM" src="https://user-images.githubusercontent.com/128402101/235008141-41d1e344-d5c0-48d6-a3fb-bebf7bc341b9.png">

Our first graph illustrates the count of drug violation incidents that occur within Boston on different days of the week. We noticed that unlike most crimes, drug violations occur more often on weekdays. Saturday and Sunday report the lowest amount of drug violation incidents. We continued to analyze this same data in our next visualization. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 29 PM" src="https://user-images.githubusercontent.com/128402101/235008185-d248e12e-49bf-4666-a8d2-fa6aaeb646b9.png">

We excluded Saturday and Sunday because of their low incident reports and analyzed Monday - Friday. In this visualization, we look at how these different days experience drug violation incidents throughout the year. Our results represent similar trends between all five days, where there’s a spike in incidents in March, followed by a decline in April, leading to a steady increase throughout the summer, where drug violations reach their peak for all days in July/August. Then, the number of violations declines steadily throughout the remainder of the year. This information is useful to know so the police department ensures they have adequate staff for the higher demand on the job during the summer. Additionally, it is helpful for the public to be more aware of the fact that drug violations are more likely to occur during the summer so the public takes adequate safety measures and avoids areas that have a lot of drug violations likely to occur.

## Question 2:

Question: During what hours and in which districts does Boston have the most drug violations? For the district and hours with the most drug violations, what street is the most popular location for drug violations? 

Importance: 

This question is important because it enables the police and public to be aware of the districts that are most likely to have drug violations occur as well as the most popular times for drug violations to occur. With this information, the police department could deploy more officers to districts that are more likely to have drug violations as well as during peak hours likely for drug violations. It is more effective to deploy more officers during peak hours to efficiently utilize their services and economically be more worthwhile. Additionally, the public would feel safer if they know more extensive measures are being taken to keep them safe during peak hours in popular districts for drug violations. The second question builds on the last question’s revelations that district A1 has the most drug violations occurring between 14-22 hours (2 PM - 10 PM). From this insight, it is important to find the streets within district A1 that are most likely to have drug violations occur on. This would further help the police department to target streets to keep officers on during 14-22 hours. Additionally, the public would be more informed of what streets to avoid during 14-22 hours to be safer and further away from any possible drug violations. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 42 PM" src="https://user-images.githubusercontent.com/128402101/235008200-aa0fd1c7-8407-4eec-8faf-7e8458dc66f3.png">

In analyzing the count of drug violations by district and hour of day, we found that there is a peak in the trend line of most districts between the 14th and 22nd hour of the 24 hour period. This indicates that across virtually all districts, drug offenses spike between 2:00 pm and 10:00 pm, and the district with the most drug offenses during this time is district A1. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 50 PM" src="https://user-images.githubusercontent.com/128402101/235008216-fd327af8-4b38-4e01-8d4d-7dca8255246f.png">

After delving deeper into this finding, we found that of the streets in district A1 between the times of 2:00 pm and 10:00 pm, the street with the most drug violations is Boylston Street- with Washington, Tremont, and Beach streets trailing behind it. Thus, an appropriate course of action would be to increase police presence on Boylson St, Tremont St, and Beach St between 2:00 pm and 10:00 pm These findings are important and useful in that they can help law enforcement narrow down in which areas and during what times they should patrol more often or dispatch more units to, to help eradicate drug-related crime. Without this analysis, law enforcement may be wasting resources by patrolling the wrong areas or patrolling areas during times drug offenses are not even likely to occur. Utilization of these findings would improve the efficiency and effectiveness of law enforcement.

## Manupulations applied to the data set for analysis:

We did not have to manipulate any data, but we did have to standardize the data set. A standardized data set focuses on transforming raw data into usable information before it's analyzed. Our data fits that description as we have quantifiable data that can be measured and adheres to the standard of being meaningful, interpretable data. Our data also has no duplicate data, irrelevant data, redundant data, inaccurate data, or low-quality data. We also have cleansed the data, ridding it of any incomplete, irrelevant, or inaccurate data. On top of all of this, we have formatted our data and it contains no 3rd party imports.

## Tableau packaged workbook

The packaged workbook containing the visualizations shown above is attached to this repository.
