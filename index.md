---
title       : The storm app
subtitle    : An app showing the financial and human impact of weather events in the USA
author      : Philip Ohlsson
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The Storm App

The Storm App lets you check the financial and human impact weather events have had on the United States between 1950 to 2011.

Simply choose whether you wish to check the financial impact of weather events by selecting: 

- Property Damage
- Crop Damage or
- Property and Crop Damage combined

Or choose the human impact of weather events by selecting: 

- Fatalities
- Injuries or
- Fatalities and Injuries combined

--- .class #id



## Visualize it!

For instance, you can check visually how the impact of Crop&Property Damage differs between state and year:

 <iframe src=' assets/fig/nvd3plot-1.html ' scrolling='no' frameBorder='0' seamless class='rChart datamaps ' id=iframe- chart20a03a0f4a70 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>


---


## Download it!

In case you enjoyed watching the visualization and wish to download the data, you can do that. 

In case you are only interested in checking out a specific state, a specific year, or only the human impact of weather events, you can do that too! Simply select your preferences, click the  download button and the data will be downloaded into a csv file.

---

## More info

- For more info on the code of the app, click here: 
https://github.com/ohlphi/weather

- For checking out the app, click here:
https://ohlphi.shinyapps.io/weather

---
