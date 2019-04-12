# Updated: Billboard top 100 time series data
## Application link
[Billboard top 100 BPM data](https://jwillg.github.io/billboardtimeseries/proj1v2.html)
## What's New
### Additions
Gridlines\
Responsive 10-class color scheme\
Individual Song Search Bar\
Top 10 => Top 100 songs displayed\
All BPM selection button\
Reduced line thickess\
One screen width change\
Additional data animations

### Deletions
Average line button\
Reset button\
Old description

## Overview
The purpose of this application is to visualize the billboard's top song data in order to compare BPM (beats per minute) using D3js. Data was obtained from kcmillersean at data.world and BPM data was obtained from tunebat. The new version tracks the songs that break the top 10 during the years 2014-2018 and observes how the songs' position changes over time.

## Using the application
View individual song BPM data by typing a song name into the search bar. On this github I've provided a text file with a list of all of the songs, so if you don't have a particular song in mind you can refer to that document. By selecting a box on the legend you can view all songs that are in the selected BPM range, or view all of the songs at once but clicking the All BPMs box. In order to view the stats of the indivual song, hover over a circle and it will diplay the song BPM, title, and artists. There is feedback for entering an correct and incorrect song title.

## Data description
All of the data used to create the visualization is included in `data.csv` and were split into smaller files to easily access the particular position that the songs are at. The data used for the creation of the graph are WeekID and BPM; BPM, Song and Performer are used for the tooltips. 

## Findings
One interesting finding was the popularity of "All I Want For Christmas Is You". Every year it will come back onto the billboard hot 100 and stay for a number of weeks, even after Christmas. 
![Image](https://i.imgur.com/ZS7zmn4.png)

Another finding was, when selecting all BPMs on the visualization, most songs tended to rise and fall around the 50th position.
![Image](https://i.imgur.com/IMlmvbN.png)

I also found it was easier to look through the songs one might enjoy. For example, since I tend to like song's with higer BPM, I can easily select the 160+, 150+,and 140+ BPM boxes and find which songs I might enjoy.
![Image](https://i.imgur.com/8z9giZT.png)

Finally, I want to reiterate how prominent songs written for movies exclusively will stay on the billboard hot 100 for a number of weeks after the movie's release date. In this example, I've selected "Earned It (Fifty Shades of Grey)". Fifty Shades of Grey was released in Feburary 2015, but stayed in the top 100 until November 2015.
![Image](https://i.imgur.com/G5WZykB.png)

# Old: Billboard top 100 time series data
## Video
Click the image below to view a video of the application.
[![Video of application](http://i3.ytimg.com/vi/D1Mz1bwLVa4/maxresdefault.jpg)](https://youtu.be/D1Mz1bwLVa4)
## Application link
N/A
## Overview
The purpose of this application is to visualize the billboard's top song data in order to compare BPM (beats per minute) using D3js. Data was obtained from kcmillersean at data.world and BPM data was obtained from tunebat. 
## Using the application
Instructions for using the application are explained in the video but there is also a condensed version of them in the live application link above.
## Data description
All of the data used to create the visualization is included in `data.csv` and were split into smaller files to easily access the particular position that the songs are at. The data used for the creation of the graph are WeekID and BPM; BPM, Song and Performer are used for the tooltips. 
## Findings
An interesting fact is the songs that are exclusively made for movie soundtracks will often crack the top 10 for a number of weeks. For instance, in this picture Earned It (Fifty Shades Of Grey) stayed in the top 10 starting from it's release date February 2015 until July 2015.
![Image](https://i.imgur.com/5JUGMv6.png)
