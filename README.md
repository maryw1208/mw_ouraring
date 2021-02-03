# Final Project Title
Analyzing Mary's Sleep Data from the Oura Ring: March 2019-August 2020
Mary's Journey Into Discovering the Quality of Her Sleep and Achieving Healthy Patterns in Her Life

## Introduction

This is the introduction to my final project: Mary's Oura Ring Analysis of Sleep Data over the last 17 months 3-2019 to 8-2020
This project will analyze Mary's Oura Ring data from March 2019 to August 2020.  

Recently, sleep science has been gathering steam and proving what should have been intuitive all along.  Our bodies don't evolve to waste time.  Sleep is central to our health and performance.  Although we remember little from our time asleep, our brains are firing and our bodies are actively repairing.

Using the data gathered over the course of the last 17 months, this project will help to uncover long-term insights and patterns so that Mary can build on healthy practices every day and over time.


This study will hopefully answer some questions. How much time is Mary investing in sleep?
How well does Mary sleep?  Is she getting enough quality sleep?  Or is she sleep deprived?
How much time does Mary spend in each sleep phase each night?
Is eight hours of sleep a night the right amount of time for Mary?  How are Mary's daily habits affecting her sleep?
Does Mary need more time in the different sleep phases?

## Data Dictionary
While there are more fields in the data set, only the fields that were used in the report for the analysis are defined.

| Field | Description |
| :--- | :--- |
| Date| Date Format. The date of the reading in mm/dd/yy.|
| Sleep Score| Integer (Percent).  Ranging from 0-100%.  Is the overall measure of how well you slept.|
| Lowest Resting HR| Integer. Is the number of times your heart beats per minute when you're at rest. Displays the lowest 10 min avg it has detected.|
| Average Resting HR| Integer.  Is the number of times your heart beats per minute when you are at rest. Displays the loweest 10 min avg it has detected.|
| Total Sleep| Integer. Refers to the total amount of time you spend in light, REM and deep sleep.|
| Sleep Efficiency| Integer (Percent).  Is a measurement of your sleep quality.  It's the percentage of time you actually spend asleep after going to bed.|
| Restfulness Score| Integer (Percent).  Percentage of time sleep disturbances occurred caused by wake-ups and restless time during the sleep duration.|
| Deep Sleep Score| Integer (Percent). Percentage of the time spent in the most restorative and rejuvenating sleep stage, enabling muscle growth and repair.|
| REM Sleep Score| Integer (Percent). REM (rapid eye movement) sleep percentage measuring the percentage of time you are in this sleep zone.  This sleep re-energizes your mind and body, and is associated with dreaming, memory consolidation, learning and creativity.|
| Sleep Latency Score| Integer (Percent). Sleep latency is the time it takes for you to fall asleep.  This is the percentage of time you fall within 15-20 min (normal) sleep latency.|
| Sleep Timing Score| Integer (Percent). The percentage of time that you are actually within the sleep zones.  Oura considers Sleep Timing to be optimal and aligned with the sun when the midpoint of your sleep falls between midnight and 3am.  A time significantly earlier or later can lower the sleep score.|
| Total Sleep Time| Integer (In Seconds - will need to divide by 3600 for hours). The total amount of time you spend in light, REM, and Deep sleep.|
| Bedtime Start| Datetime.  The date and time estimate of the time you went to bed with the intention to sleep.|
| Bedtime End| Datetime.  The date and time estimate of the time you woke up with the intention to be awake. The time you got out of bed.|
| Total Bedtime| Integer (In Seconds). The difference between Bedtime Start and Bedtime End.|
| Deep Sleep Time| Integer (In Seconds).  The time you are in the REM Sleep Stage 3 which is the deepest sleep phase.|
| Light Sleep Time| Integer (In Seconds).  The time you are in N1 and N2 sleep, which are the 1st 2 stages of NREM sleep. This is somewhere between sleep and wakefulness.|
| Awake Time| Integer (In Seconds).  The time spent awake in bed before and after falling asleep.|
| Respiratory Rate| Float. The number of breaths a person takes per minute.|
| Lowest Resting HR Score| Integer. The number of times your heart beats per minute when you're at rest taking the lowest number. It's a good measurement of your sleep quality, recovery and overall health.|
| Average HRV| Integer. Average Heart Rate Variability is linked to your autonomic nervous system (ANS) and the balance between the parasympathetic (rest-and-digest) and sympathetic (fight-or-flight) branches. By balancing the two forces, the ANS helps you respond to daily stressors and regulate some of your body’s most important systems, including heart rate, respiration, and digestion. HRV is the most effective way of estimating your ANS balance, as it directly impacts your heart’s activity.|



## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* http://ouraring.com - Oura Ring Website
* https://ouraring.com/the-pulse - Oura Ring The Pulse Resource Site
* http://www.heart.org - American Heart Association
