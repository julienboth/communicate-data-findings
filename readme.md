# 911 Emergency Calls in Montgomery, PA
## by Julien Both

This Project was a submission for the Udacity Data Analyst Nanodegree


## Dataset

The data consists of information regarding 663522 Emergency Calls for Montgomery County, PA including latitude, longitude, description, zip, title, timestamp, commune and adress

The dataset comes from kaggle [here](https://www.kaggle.com/mchirico/montcoalert) The dataset was approved by  Udactiy mentor Michal K. [here](https://knowledge.udacity.com/questions/299578)


## Summary of Findings

EMS has the most calls in the period, followed by traffic incidents and the least amount of emergency calls are fire classified

23 of the 68 communes had more than 10000 calls. Lower Merion has a huge gap the second one which is abington.

It looks like the amount of calls at the weekend is signficant lower than on week days.

In Average there are between 250 and 500 calls a day. But there are three big outlier 02.03.2018, 15.11.2018 and 03.06.2020

Interesting to see is that most of the calls are at daytime, especially in the afternoon hours. And than between 22-23 o'clock again. 

Most of the calls are mid of the month and at the start of the month 

Each reasons has the highest amount of emergency calls on friday. Traffic e-calls have a signifcant lower amount on weekends. EMS is close to constant. Fire calls are  on average 4 times less likely than EMS

The rapid increase of the emergency calls at the three days: 02.03.2018, 15.11.2018 and 03.06.2020 come from traffic accidents and two times in combination with fire alarm calls

As seen above at the beginning of the months as well as at day 15 are the most calls for emergency, 13 and 17 pm are most calls on 15 of the month

EMS calls increases at around 8 o'clock and has it peak between 10-12 am. There is no hugh different between the days of the month. Fire alarms seems to have a peak at the start of the month but is relativly constant. Traffic alarms have a peak at 15th of the months in the afternoon hours.

Interesting to see is that EMS calls mostly happens shortly before noon on weekdays, Fire alarms have a high probability to happen wednesday between 14-18 o'clock. Traffic alarms are most likely fridays between 14-18. There are way less traffic alarms on weekends.


## Key Insights for Presentation

For the presentation i focused on the calls in the time period, to understand at which point in time it is more likely to have a traffic related call or a EMS related call. Therefore i started to introduce the general dataset and than focusing on the dates and the different types

The dataset contains Emergency 911 calls in Montgomery County located in the Commonwealth of Pennsylvania. The attributes chosen include: type of emergency, time stamp, township where the emergency has occurred.

Emergency calls per commune
23 of the 68 communes had more than 10000 calls. Lower Merion has the most calls overall followed by Abington, which has signficant less calls. Lehigh County seems to be the safest commune with the least amount of calls. To illustrate that i added a horizontal red dotted line

Type of call and weekdays
Each type of call has the highest amount of emergency calls on friday. Traffic calls have a signifcant lower amount on weekends. EMS is close to constant between all days. Fire calls are on average 4 times less likely than EMS.

Amount of Calls in the period per day
In Average there are between 250 and 500 calls a day. But there are three big outlier 02.03.2018, 15.11.2018 and 03.06.2020 As we can see in the diagram, the rapid increase of the emergency calls at the three days: 02.03.2018, 15.11.2018 and 03.06.2020 come from traffic accidents and two times in combination with fire alarm calls


Heatmaps
The next subslides will show different comparisions of Heatmaps for each of the different types. In the multiveriate visualisation i wanted to see whether there is a difference for the three reason in terms of the day of Month and the time of the day. As well as the same for the weekday and the different times

Heatmap 1 - Hour of the Day to Day of the Month
EMS calls increases at around 8 o'clock and has it peak between 10-12 am. There is no hugh different between the days of the month. Fire alarms seems to have a peak at the start of the month but is relativly constant. Traffic alarms havea peak at 15th of the months in the afternoon hours.

Heatmap 2 - Hour to Weekday
Interesting to see is that EMS calls mostly happens shortly before noon on weekdays, Fire alarms have a high probability to happen wednesday between 14-18 o'clock. Traffic alarms are most likely fridays between 14-18. There are way less traffic alarms on weekends.


