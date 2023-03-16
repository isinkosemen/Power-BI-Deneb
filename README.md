# My Showcases of Custom Visuals in Power BI with Deneb
Here is a collection of my showcases that I built in Power BI with Deneb using Vega and Vega-Lite libraries.
Feast your eyes on some of my best work.

# The Economist's Big Mac Index - Dot Plot Chart With Dynamic Text
I used Power BI slicers for Base Currency, and Index Period filter options. The rest of the custom visual was built in Deneb with Vega-Lite library.
I used params to change the color of the points and display the dynamic text when I hover and click on each one of them. The most challenging part 
of re-creating this visual was applying different font colors to different parts of the text. I had to break down the text to apply multiple colors, and 
I used the Monospace fixed-width font, so that I could get even spacing between each block of text.

Here is [the pbix file](https://github.com/isinkosemen/Power-BI-Deneb/blob/main/the-economist-big-mac-index/the-economist-big-mac-index-pbi.pbix). 

Here is the [url link](https://www.economist.com/big-mac-index) of the Economist's original work on Big Mac Index.

https://user-images.githubusercontent.com/28147353/224336853-8e40949c-3fbc-46cd-8114-244441cfc37d.mp4

# Information is Beautiful Creative Challange 2023
Here is the [Power BI interactive dashboard](https://isinkosemen.com/a_decade_of_electricity_production.html) I created for the 2023 "Information is Beautiful" creative challange. 

I used [Deneb pattern fills](https://deneb-viz.github.io/pattern-fills) to represent and highlight each source for the electricity production and their share between 2010 and 2020.

My interactive dashboard was included in the [interactive longlist](https://informationisbeautiful.net/visualizations/world-dataviz-prize-2023-interactives-longlist/) chosen by the jury.

<img width="664" alt="Screenshot (850 corrected)" src="https://user-images.githubusercontent.com/28147353/224347262-067651a0-1982-4a11-a1ec-bfae08b9a4ee.PNG">

# Turkey's Ring of Fire

This interactive Power BI Deneb custom visual shows the earthquakes which took place in Turkey between the 6th and 8th of February 2023. 

Everything was created by using the Vega-Lite library.

The red line shows the main fault lines in the region.

Here is the link for the [pbix file](https://github.com/isinkosemen/Power-BI-Deneb/blob/main/turkey-ring-of-fire/turkey-ring-of-fire.pbix).

I downloaded the GeoJSON data from [geojson-maps.ash.ms](https://geojson-maps.ash.ms/).

For earthquake locations I used [USGS earthquake data](https://earthquake.usgs.gov/earthquakes/search/). I also used «Plates and Faults layers v2» to get the coordinates of Turkey’s main fault lines from [usgs.maps.arcgis.com](https://usgs.maps.arcgis.com/home/index.html).

https://user-images.githubusercontent.com/28147353/224446975-b57aae1c-9c20-4b77-86cb-bff7b07152fc.mp4


