# Term-Project-Data-Science
Term project based on the statistics of the players that were considered into the hall of fame.

## Motivation for this project

When we started this project we were curious about how fair were the votations for the Baseball Hall of Fame. With this concept in mind we started gathering data and adjusting it for further analysis. We then perform multiple types of analysis such as: hypothesis testing, prediction (regression) analysis, classification,  time-series analysis, clustering, and finally verified them. We will present the conclusion that we found in this repository.


## Prerequisites

### Built With

* [RStudio](https://rstudio.com/) - The software used.
* [R Language](https://cran.r-project.org/) - Programming language used.

### Libraries Required
This project was made in the R language, utilizing RStudio.
The Libraries that are require for this R project to properly run are:

```
library(tidyverse)
library(forecast)
library(knitr)
library(party)
library(caTools)
library(Metrics)
```

### Gathering the data

The data for this project was gathered from the webpage [Baseball refence](https://www.baseball-reference.com/awards/awards_2018.shtml).

Our team collected data about the hall of fame from different years starting in 1989 through 2019. All the different years were then summarized into one data frame.

### Analysis on the data

The data was divided in different sub divisions throughout the project in order to perform hypothesis testing, prediction (regression) analysis, classification,  time-series analysis, clustering, and finally verified them. These divisions are explained in the project itself, so a clear understanding can be achieved.

### Visualizations
These are some visualization that were obtained from our analysis. they will provide a summary of what our conclusions were.

<details>
           <summary>Hypothesis testing</summary>
           <p>
         
The following visualization shows non pitchers' voting percentage for entering the hall of fame, according to their hits. Also, it states if they made it to the hall of fame or not.
![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz1.png?raw=true)

The following visualization shows pitchers' voting percentage for entering the hall of fame, according to their Strikes Out. Also, it states if they made it to the hall of fame or not.
![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz4.png?raw=true)
</p>
</details>
<details>
           <summary>Linear Regression prediction</summary>
           <p>
             Comparison among the actual voting percentage, our model predicted percentage, and the trend predicted percentage.

![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz7.png?raw=true)
  </p>
         </details>
<details>
           <summary>Classification</summary>
           <p>
             Non pitchers decision tree. It states if they made it to the hall of fame depending on a statistic.
             
![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz8.png?raw=true)
  Pitchers decision tree. It states if they made it to the hall of fame depending on a statistic.
             ![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz9.png?raw=true)
  </p>
</details>
<details>
           <summary>Times series analysis</summary>
           <p>
  Prediction for next years candidates' average strike outs according to our time series analysis.
             
 ![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz12.png?raw=true)
             
  Prediction for next years candidates' average hits according to our time series analysis.
             
  ![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz15.png?raw=true)
   
  As shown, this analysis couldn't be properly perform due to our data.
  </p>
         </details>
<details>
           <summary>Clustering</summary>
           <p>
  Clustering analysis that demonstrates the difference in statistics between pitchers and non pitchers. It shows that both classes have similar cluster even though there is a difference in the quantity of each class.
  
  ![alt text](https://github.com/datamonsters10/Term-Project-Data-Science/blob/master/Project%20Graphs/Viz18.png?raw=true)
  </p>
         </details>

## Authors

* **Claudio Lupi** - *The Brain*
* **Eduardo Reyna** - *The Muscle & Looks*
* **Sebastian Calzadilla** - *The Soul*


## License

This project is licensed under the STU License(Dpt. Of Science).
## Acknowledgments

* **Dr. Mondesire, S.** - *Spiritual guide*
* **Max Frank** - Helped to correct code
* **God** - *He was always there*


