# Heat-Map
A tool used to pull location data from a spread sheet and graph the number of occurences on a choropleth heat map.

Using a .xlsx file with the column Location that includes the relevant location data. This program was used to count all occurences of state specific data. 

The program would then combine any data from states that were seperated by North and South. For example, data from North Texas and South Texas would be combined into one to aggregate all the counted occurences.

This would then use the GeoJSON date from the included map to color each state based on the number of occurences. 

I have also included tool tips so that when you hover your cursor over each state it will show the State Name and number of occurences. 

After the program is finished running it will export a .html file that can be opened in any web browser.

This was used to count the number of incoming tickets from each state in order to isolate large outages by State or Region. 
This could then point to possible gateway, region, or ISP outages.
