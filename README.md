## ArcGIS Project
###### This program uses [ArcGIS](https://developers.arcgis.com/), [JavaScript](https://www.javascript.com/), [HTML](https://www.w3schools.com/html/), and [CSS](https://www.w3schools.com/css/default.asp)

This is my first project using a GIS, and it was a lot of fun! I'm excited to make more with this. In it's current form, this displays a webpage with a map and marks the top 100 mountain peaks according to wikipedia as of December of 2020. This is not connected to Wikipedia in any way, and the GeoJson is included with the files. The GeoJson is limited, but were ordered by highest elevation to lowest. As such they are color coded by order of apearence in the GeoJson file. More will be explained later in the program.
#### Execution

Installing ArcGis will not be needed, but this does use [AJAX](https://www.w3schools.com/xml/ajax_intro.asp) and as such will need a local server to run. I recommend [XAMPP](https://www.apachefriends.org/download.html) which I used to develop this. Here is a better tutorial for installing that than I can give, which may be found [here](https://www.youtube.com/watch?v=-f8N4FEQWyY). 

#### Features

There not much interaction beyond a map that is present here, however, it does have some additional features.

1. Each peak is marked by a circle ranging from <span style="color: gold;background-color: black">gold</span>, <span style="color: orange">orange</span>, <span style="color: purple">purple</span>, <span style="color: blue">blue</span>, <span style="color: green">green</span> and <span style="color: #bbbbbb; background-color: black">white</span>. These in theory show the elevation in comparision to the other peaks. Gold is the hights, orange is second, purple is third and so on until white wich have the lowest evevation.<i> I say this is in theory, becuase there is no data in the GeoJson that describes evelation. They are simply organized in order of elevation. </i>The colors really describe the order in which they apear in the GeoJson.

2. Clicking the markers will pull up a pop up that tells the name of the peak and gives a link to where its found on Wikipedia. 
