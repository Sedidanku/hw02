# hw02 -Optional TidyTuesday
This data-set, earn.csv, comes from a 2021 TidyTuesday Challenge. The listing is called "Employment and Earnings". The 'earn.csv' file was sourced from the U.S Bureau of Labor Statistics.  
The visualization I made showcases the change in median weekly earnings for those who are employed, by race, from 2010-2020. I used gg(animate) to create an animated scatterplot of median weekly earnings vs number of people employed in that race. For the visualization, I animated the scatterplot by the variable 'year' using 'transition_time(year)', which sets the transition of each frame in the animation by a time variable. Additionally the visualization has a title that changes based on the year using Year:frame_time{}. For the scatter plot I set made the x axis median weehly earnings, the y axis the numberof employed people in that group ,colored the data points based on race, then set the alpha = 0.5 for aesthetic purposes.
Analyzing the visualization, it appears that the number of people employed accross all groups has increased from 2010 to 2020. The largest employed labor force is white people, followed by black people then asian people. Additionally it appears that median weekly earnings has increased for all groups, with asian people reporting the highest median weekly income. A limitation of the data that I noticed was that there were not enough ethnic categories, since Latino people were completely excluded from the analysis. Attached here is a gif of my visualization.

![file2552e79272cb9](https://user-images.githubusercontent.com/105371806/174152607-ad1c02a6-b056-4a6f-8bc7-d263646aee5d.gif)
