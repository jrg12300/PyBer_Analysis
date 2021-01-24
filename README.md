# PyBer_Analysis

Overview of the analysis:

  The purpose of this analysis was to help a ride sharing company (PyBer) better understand their rides and fares across different cities. Pyber provided us 2 data sets: 1) a list of every city they operate in with the # of drivers and the city type (rural, suburban, urban 2) a list of every rideshare from 1/1/2019 - 5/8/2019 with the city, fare, and ID number. We took this data, combined it into 1 dataframe using jupyter notebook, and visualized it using pivot tables and line graphs. The main analysis we did was break down fares and rides by city type. Using pivot features in pandas, we were able to plot weekly fare totals by city type, and better understand the discrepancies. 


Results:

  As expected, there were some noteworthy differences between the rideshares in different city types. 
[INSERT DF PIC HERE]

  First of all, from the "Total Rides" column, it is obvious that there are much more rideshares in urban cities. this makes sense because more people live in urban areas, and parking in urban areas can be very difficult. 
  
  The second column of this summary ("Total Drivers") is suprising. There are more registered drivers in urban areas than there are rides given. This doesn't make sense, so more research should be done by the comapny into why there are so many drivers registered that are not giving rides. This anomoly is only true for urban cities.
  
  the 4th column of this summary is the "Average Fare per Ride". As population density goes up, fares seem to go down. This is explained by supply and demand - there are more drivers in the urban areas in comparison to the rides given.
  
  The last column of this summary is the "Average Fare per Driver". This shows the total fares (by city type) divided by number of drivers. Similarly to the 4th column, the urban drivers are making less money. 

  Here is the line plot made using Matplotlib:
[Insert Line Plot PNG Here]

  This plot shows the information given in the 3rd column of the summary table, but shows it's changes over time. the last data point goes down because we limited the analysis to just data between 1/1 and 4/29. This shows that weekly fares have not improved over time from 1/1 - 4/29. PyBer would like to see total fare increasing over time so that they can grow the company.

Summary:

  In summary, the PyBer need to find a way to grow their company. They are not currently making very much money, and their revenue has not increased notably over the past 5 months. Here are some recommendations:
  
  1) Pyber should not focus on expanding into other cities, especially other urban cities. PyBer is in 66 urban areas and has only given 1,625 rides. That is an average of 24.6 rides/city. Pyber has plenty of drivers in urban areas, but not enough customers. If PyBer is going to continue operating in urban areas, it should focus on marketing so that more riders use the service. 
  
  2) PyBer should not focus on hiring/attracting more drivers in any city. If we look at the summary and compare the number of drivers vs the number of rides, each driver is not giving that many rides under PyBer. 
  
  3) PyBer should look into reducing fares. This may attract more customers, which is a need. Also, if some drivers decide to leave PyBer (due to lower wages), it is okay because PyBer already has too many drivers in comparison to the rides.
  

