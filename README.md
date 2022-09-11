# Project: Investigating a No Show Appointment Data Set

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
<li><a href="#limitations">limitations</a></li>
</ul>

<a id='intro'></a>
## Introduction

### Dataset Description
> Despite new technologies being invented to make sure everyone has easy access to healthcare facilities, a number of hospitals still have patients not showing up for their scheduled appointments. This causes hospitals to incur loses in running their facilities since they thrive on patients showing up.

> This analysis will provide more insights into why patients do not show up for their appointments and provide possible solutions to improving show ups.

> The dataset used for this analysis was collected from hospitals in Brazil. This data contains 100,000 medical appointments from Brazil and is focused on whether or not patients showed up for their appointment.

> This dataset contains 14 unique variables **(Patientid, Appointmentid, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhod, Scholarship,Hipertension, Diabetes, Alcoholism, Handicap, SMS_received and No_show)**
‘ScheduledDay’ tells us on what day the patient set up their appointment.
‘Neighborhood’ indicates the location of the hospital.
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
'No_show' last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

<a id='wrangling'></a>
## Data Wrangling
The next step in the data Analysis process is to wrangle our data. This is where we gather, assess and clean our data. Our dataset will be uploaded, checked for cleanliness, and then trimmed and cleaned for analysis

### Data Cleaning
After discussing the structure of the data and the problems that need to be addressed, it is now time to perform those cleaning steps on our dataset.

<a id='eda'></a>
## Exploratory Data Analysis

in this section, the dataset will be explored and augmented to maximize the potential of our analysis and visualizations. Exploring involves finding patterns and visualizing relationships between variables. Also, outliners will be removed if there to create better features.

### Question(s) for Analysis
 Some questions that will drive us into meaningful insights of this datasets are:

    1.Does the patient's age play a role in him/her showing up?
    2.Does the patient's gender play a role in a patient showing up?
    3.What is the time frame between the scheduled Day and the appointment Day? Does it impact the patients ability to show up?
    4.Is there a possibility that patients enrolled in the Brasilian welfare program Bolsa Familia showed up more?
    5.Is an SMS reminder the reason why some patients show up and others do not?
    6.Is proximity to the hospital a factor for no show?

  <a id='conclusions'></a>
## Conclusions
- Comparing age group with ability to show up, its noticed that people between the ages of 30 to 60 show up more for their appointment as well as people above 100, this could be because they are more health conscious and are constantly engaged in physical activities. There is no clear correlation between patient age and their ability to show up.

- Females make 65% of the total population and are more likely to show up for appointments compared to                        their males. This can be due to the fact that probably some females were pregnant and had to make it to their antenatal appointment also most females tend to be health conscious than males.

 - From the above analysis, waiting time plays a difference in clients showing up for their appointment. Analyzing the difference between schedule and appointment shows that 25 percentile had same day call up while some patient had to wait as long as 179days after scheduling an appointment.

    <a id='limitations'></a>
## Limitations
   - The data set was not vast, as the data was collected within a small time frame. Therefore not enough correlation between no show and the other variables.
    - The data set is not recent, therefore cannot be applied in recent times. An update of the data could have helped in drawing more solid conclusions on relationships between variables.
    - https://en.wikipedia.org/wiki/2016_in_Brazil#May. Researching into the dates shows that, missed appointments were on days when there were quite a number of political activities in Brazil Like the impeachment from the president of Brazil which could have had an impact on no shows.
