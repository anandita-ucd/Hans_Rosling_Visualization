# Hans_Rosling_Visualization
This is a data visualization project similar to Hans Rosling Visualization.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
This text file contains all the features implemented in this replica of the Channeling Hans !
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

- All countries belonging to the same region share the same color.
- A year label in the background of the bubble chart to understand which data is for which year while the animation is on.
- A start/pause button to start or pause a continuous animation of the change in country statistics from year to year (1900 – 2015).
- Hovering on each bubble will display the name of the corresponding country. Also the unhovered bubbles will be blurred out during this time. 
  On mouse out, it will return to its original state. This entire feature will work as it is while the animation is played, as well as when its not played.
- Clicking on each bubble will display the details (GDP and Life Expectancy) of the particular country. Unselected bubbles will be blurred out during this time.
  This entire feature will work as it is while the animation is played, as well as when its not played. 
  To return to its original state, you need to click on the "Reset Selection" button on right hand top corner.
- Data for a particular year can be viewed by selecting a year from "Select Year" dropdown at the left hand top corner.
  If a year is selected while the animation is being played, the animation will be paused and data of the selected year will be displayed.
  If animation is played again, the animation will restart from the year when the animation got paused.

- Two bar charts, one showing number of countries per region (regions are colored appropriately), another showing number of countries with each government type.
- A year label at the top of the charts to understand which data is for which year. The year corresponds to both the above mentioned bar charts.
- For the region vs number of countries bar chart, there are labels for each bar showing the number of countries in that region for a particular year.
  This label will be displayed when you hover on a particular bar. Hovering on each bar will blurr out the other unhovered bars.
- Both the bar charts will display year wise data while the animation is played, or when a year is selected from the "Select Year" button.
- A particular country can be selected in two ways. First way is already discussed in Part 1, where clicking on a bubble wil display the statistics of that country.
  But here, you will have to search for the correct bubble. So we have kept another option to select a particular country.
  This can be done from the "Select Country" dropdown at the top which contains the list of all the countries. 
- Trace of a particular country in a static visualization can be viewed by clicking on "See Trace" button. 
  This button will only appear when a country is selected in any of the two ways (bubble selection OR country selection).
  Once "See Trace" is clicked, the visualization will become static. Now if you hover on each bubble, the corresponding year will be displayed.
- All the above features will work while the animation is played, as well as when its not played. 
  To return to the original state, you need to click on the "Reset Selection" button.
  
  In the bar chart showing number of countries per region, we have added the following extra features:
- On clicking each bar, the countries belonging to the corresponding region will be displayed in the bubble chart, blurring the other countries. 
- And now if the animation is turned on, the bubble chart will show only those selected countries. 
- By this you can view the yearwise statistics of the countries belonging to a particular region.
- In order to view all the countries again, you can click on the "Reset Selection" button at the top which removes all selections and the visualization returns to its initial state.
- If you select a country not belonging to the selected region, then the region selection will be reset to its initial state.

