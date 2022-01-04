##**Traffic Incident Management**

*Capstone Project for Fulltime Data Analysis Cohort #5 program at Nashville Software School.*

### **Table of Contents**  
- [Executive-Summary](#Executive-Summary)
- [Motivation](#Motivation)
- [Data Questions](#Data-Questions)
- [Schedule](#Schedule)
- [Data Sources and Tools](#Data-Sources-and-Tools)
- [Known Issues and Challenges](#Known-Issues-and-Challenges)
- [Links to Tableau Public and Video](#Links-to-Tableau-Public-and-Video)
- [Approach Outline](#Approach-Outline)
- [Acknowledgements](#Acknowledgements)


###**Executive-Summary**
Traffic congestion is a significant problem in growing cities throughout the country. Nashville has been growing steadily for the past decade. I wanted to research a significant problem that impacts people on some level. One of the first things that comes to mind is Traffic. I wanted to take a closer look behind the scenes and review the data and see what kind of story it tells for incidents in Tennessee. The overall project will focus on the incidents that occur on the interstate and primary roadways in Region 3 and the effects, and results based on the data and trends discovered.


### **Motivation**  

I have been fascinated with the growth and evolution of Nashville, TN since moving here a decade ago. The population, construction, real estate market, cost of living, traffic and of course incidents have risen unquestionably. Additionally, I have noticed that the weather plays a crucial role regarding incidents, which cause traffic. The motivation behind choosing this project was inspired to become more knowledgeable with the data, be able to analyze and clean the data, while creating a dashboard that can provide insight. Known assumptions may include weather, time of day & year (school year), events, growth, construction, traffic, covid, and State vs City Operations depending on data. If one drives a vehicle, then they are affected by traffic in one form or another. The motivation behind the analysis stems from a passion to better understand incident and traffic management to add to a possible solution or to inform regarding the challenges. Potential challenges that may arise is gathering data from the government and being able to work with it.
Therefore, my motivation is to make a difference and create an informative review to the collective community.
*Back to [Contents](#Contents)*


### **Data Questions**  

- At what level of confidence can the location of an incident be forecasted in Nashville, TN based on the data that has been collected?
- What trends, occurrences, or factors increase the probability of incidents in each location?
- Based on the data analysis, can trends and commonalities be presented to provide knowledge and insight for decision making?
- Describe the interactions and outcomes of the data.
*Back to [Contents](#Contents)*


### **Schedule**

11/15/2021 ..... Get the Data   
11/29/2021 ..... Clean & Explore the Data
12/10/2021 ..... Create Presentation of your Analysis
12/17/2021 ..... Internal Demos  
01/06/2022 ..... Demo Day!     
*Back to [Contents](#Contents)*

### **Data Sources, Date Period and Tools**  

**Data Sources**   

This project uses data that was requested from TDOT Operations and the Asset Management Office within TDOT’s government department.
-	Tennessee Department of Transportation (TDOT): www.tn.gov/tdot
-	Traffic Operation Division: www.tn.gov/tdot/traffic-operations-division
-	Asset Management Office: www.tn.gov/tdot/maintenance/asset-management-office
-	National Weather Service: www.weather.gov
-	Visual Crossing Weather: www.visualcrossing.com  

Documentation from the Federal Highway Administration Office was used as a resource to better understand the Traffic Incident Management measures and practices.
*Back to [Contents](#Contents)*

**Date Period**

-	Incident data is from: 11/01/2020 – 10/31/2021
-	Weather data is from: 11/01/2020 – 10/31/2021
o	Daily
o	Hourly

**Tools**

-	- `Excel`, Microsoft 365 MSO (Version 2111 Build 16.0.14701.20254) 64-bit  
-	- `Jupyter Notebook`, version 6.3.0
-	- `Python/Pandas`, version 3.8.12 for exploration and aggregation of the data
-	- `Tableau`, version 2021.3 for creating the interactive dashboard
-	- `Git`, for version control
-	*Back to [Contents](#Contents)*


### **Link to Tableau Story**

- Tableau Story:
*Back to [Contents](#Contents)*

###**Incidents clustered within interactive map**

Cluster Map



### **Known Issues and Challenges**  

** Issues with missing Latitude / Longitude Coordinates**
-The incident data sets did not including latitude and longitude coordinates, which resulted with working with another department within TDOT to obtain the coordinates.
- The requested coordinates that were obtained from TDOT’s Asset Management office created a challenging conversion. The mile marker locations included in the file needed to be converted to GPS coordinates.
- The mile market locations were not always provided creating a challenge for extensive research in locating the exact mile marker locations.  
- Merging the weather data with the dates in the incident data sets presented challenges
*Back to [Contents](#Contents)*


### **Approach Outline:**    

- **ETL** the extraction process was obtaining the data from TDOT, AMO, and extracting data from National Weather Service, and Visual Crossings Weather. Analyzed the data to determine what transformations will be needed and if any additional data will be needed. Load data into Python
- Determine what the **MVP** is for the graphs, charts, and interactive dashboard.
- **EDA** Outline of primary steps
    - Analyze data types and what additional data is needed
    - Review the amount of null data
    - Examine the values in each column for similarities and relevance to MVP & data questions
    - Understand the direction to review from the numerical values  
- Determine the best methods for merging data sets
- Review the data to facilitate what graphs are needed in the dashboard
- Explore the answers to the data questions
- Validate that the graphs display correct information, with no *irrelevant* data included, and no *relevant* data inadvertently excluded
- Create charts and graphs
- Create and format dashboard
- Prepare presentation
- Record demo    
*Back to [Contents](#Contents)*


### **Acknowledgements**

I would like to express my biggest thanks to all of those that were part of this journey that I embarked on. Finding enough words to explain how incredible this experience was is near impossible for me. I would like to express my gratitude for the instructors and staff at  **Nashville Software School.**

- The biggest thanks go out to our instructors - **Chris Wright,** Instructor, **Josh Rio-Ross,** Assistant Instructor, **Chip Hubbard,** Assistant Instructor, **Toni Kim,** Assistant Instructor, Mahesh Rao,** Program Manager, and **Michael Holloway,** Program Assistant/Instructor.
     - They took on the challenge of having a 100% remote class and ensuring that daily guidance was given with great patience to ensure that no students were left behind.  
     - Thank you for ensuring that we downloaded the right versions of software to being mindful in asking the introverts to speak up more and the extroverts to tone it back, while squeezing an abundance of information into 15 weeks.
     - The four of them provided great advice, challenges when we were up for them, and a healthy balance of levity and seriousness to ease the hard days that were part of the process.

- **Marla Lamont,** Director of Career Development, has provided an amazing amount of support for our career journey: Three rounds of resume reviews, several mock interviews, panel discussions with local data analysts and hiring managers, feedback throughout the journey, demo day, and so much more. We couldn’t have done it without you. Bravo!

- **Ashley Canino,** Senior Career Development Specialist, has provided an amazing amount of support for our career journey: Three rounds of resume reviews, demo day, reaching out to provide any additional support needed and so much more. Well Done!

- **Michael Frieh,** Career Development Specialist, has provided an amazing amount of support for our career journey: Three rounds of resume reviews, several mock interviews, panel discussions with local data analysts and hiring managers, demo day, and so much more. Thank you for stepping into your role mid-cohort and doing a fabulous job. You Rock!

- **Haley “Zap” Zapolski,** Employer Engagement Manager, has provided an amazing amount of support for our upcoming job search. The plethora of emails that present possible opportunities came through the pipeline daily. What an abundance of excitement it brought to see what was possible. Keep it coming!

- **My classmates** I absolutely adored! What an awesome class that made time for one another and provided great examples of perseverance, helpful collaboration, and support when needed.  

- I am forever grateful to **John Wark,** Founder and CEO, and **all staff** of NSS for their commitment to providing opportunities to those who are underrepresented in technology fields. They have created an incredible organization and continues to give and produce quality intentional talent. Keep it up!

My career pivoted overnight from a promotion as a software engineer. The transition was fast and overwhelming that led my desire to receive a formal education in data analytics. I was inspired and supported by my fiancé, **Adan Moncivaez** from the decision to enroll in the Full Time Data Analytics course. Learning new skills and being able to showcase my new skills proved helpful with any topic that had a dataset to provide results that are useful.
*Back to [Contents](#Contents)*
