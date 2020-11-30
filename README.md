# Interactive Maps with Folium!

Author: Claire Morehouse
Date: November 30th, 2020

## What I learned in this lab
This lab was very informative and introduced me to both the python library Folium and Pandas dataframe while also made me consider the flaws of aggregating point data in particular ways. 

In terms of technical skills/concepts, through the tutorial, I learned about how a chloropleth maps can be created through using the python library Folium and pandas dataframe. From what I could gather, essentially the chloropleth map populates  through accessing the value for the polygon zipcode feature through the pandas dataframe; and the value informs which color the that particular polygon for that zipcode is in the chloropleth map. In addition, the chloropleth map looks in the GeoJSON and finds that associated shape info for the particular zipcode which determines the geometry for that shape. 

The main purpose of this lab is to consider what is the best way to conduct data visualization for a the data we have. For example, the first chloropleth map of point data for zip codes is not particular helpful for showing patterns for point data because zip codes aren't connected to human phenomena besides mail delivery. This tutorial taught me about the MAUP phenomena, or the "Modifiable Areal Unit Problem" where the same data can look very different in chloropleth format depending on the size or shape of the geography and where the points respectfully fall. Comparing the first Chloropleth map(s) with the point map, I think the point map shows a more accurante distribution of Starbucks in LA County. 

The final part of this lab described proper technique to create a chloropleth map using appropriate geographies. I learned the value of mapping rates instead of counts, as well as that states are great geographies to use because employment laws are
specific to each state.

