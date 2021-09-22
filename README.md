# CityBike Program Viability Evaluation and Report

## Overview of Analysis:
The purpose of this analysis was the evaluation of bike sharing usage data obtained from CitiBikeNYC.  The data was representative of usage data for New York City for the month of August in 2019.  A series of charts and graphs were developed within Tableau Public to provide an asthetical demonstration of key points of information for the usage of said program in New York City.  This information was then taken and applied towards a more generalized evaluation to determine the viability and potential success of a similar program in Des Moines, Iowa.  

###  Resources:
*    Data:
    *  The trip data used in this evaluation/analysis was obtained from Citi Bike NYC.  Due to the size of the file, the full CSV file cannot be included in this report but can be obtained from https://www.citibikenyc.com/system-data.  The specific file used for evaluation was 201908-citibike-tripdata.csv.  
*  Charts/Reports Created:
   *  [Tableau Story Link](https://public.tableau.com/app/profile/jeffrey.purvis/viz/CitiBikeDataEvaluation/Bike-shareProgramViabilityEvaluation?publish=yes)
*  Software Used:
      *    Jupyter Notebook, Tableau Public 2021.3.0(20213.21.0822.2038)64-bit


##  Results of Analysis:
The following is a description of each visualization run for the dataset.  The visualizations themselves can be found via the Tableau Story Link listed under Resources.
*  Peak Hours of Use:

This chart represents the daily use of the bike-share bikes per hour of the day for the month of August 2019.  According to the data displayed, the peak hours of 5:00 PM and 7:00 PM.  This time range represents an approximately 30% increase in use compared to the next highest time range.  

*  Trips Per Weekday per Hour:

This chart is a heatmap representation of further peak usage data.  The data shows the darkest concentration of usage times being between the hours of 7:00 AM and 9:00 M-F (typical start of business day hours), 5:00 PM and 7:00 PM M-F (typical end of business day hours), and weekends between 10:00 AM and 6:00 PM.  

*  Checkout Times for Users:

This chart shows the amount of bikes that were used for 3 distinct ranges of time:  Less than 1 hour, 1 hour, and 2 hours.  The chart shows that the largest concentration of use was for periods of approximately 5 minutes with the amount of bikes used decreasing proportionately with the length of time from there.  

*  User Trips by Gender by Weekday:

This chart shows the amount of use demonstrated by Subscribers to an ongoing service vs. casual customers.  It shows that the majority of the use is from those that are regular subscribers to the business. This chart also begins to show a significant difference in the demographics of use, showing male subscribers as having a higher usage rate. There does not appear to be a significant gender usage difference for non-subscribers.

*  Gender Breakdown 

This chart shows the demographic breakdown of users of the program based on gender. Males make up 65% of the usage base for the program with females representing  25% and unknown (unreported) representing 10%.

*  Checkout Times by Gender:

This chart further breaks down the information provided in the previous checkout times chart by showing the breakdown of use per gender, showing which gender tends to utilize the service the most and for how long.  This chart clearly shows that males have the highest usage rate overall, but also for shorter periods of time.

*  Trips by Gender Per Weekday Per Hour:

This chart provides further visualization breakdown of the amount of use per the hour of any given day based on the gender of the user.  The information clearly shows that the more concentrated areas of use are during the weekday hours of 7-9 AM and 5-7 PM, with males representing the greatest concentration of users during those times.
