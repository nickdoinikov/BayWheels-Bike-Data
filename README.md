Date created: 17 June 2020

### Communicate Data Findings

This project in the last part of the ***"Data Analyst Nanodegree"*** by Udacity. In this Project, I briefly wrangled and thoroughly analysed a dataset of the bike company BayWheels.
The two main goals of this project were:

_1. Perform **Exploratory Data Visualisation**._

This part of the analysis has multiple helps to do the following things:
  * understand the patterns and relationships present in the data;
  * perform statistical analyses;
  * build conclusions and findings

_2. Perform **Explanatory Data Visualisation**._

This part of the analysis has a goal of being able to communicate the results to
others. This part is quite similar to the exploratory part, but requires much
more visual polishing and explanation.

### Summary of Findings

In the exploration, I found that there are some very visible tendencies in terms
of trip duration.

First of all, the average trip duration is around 600 seconds (10 minutes), but it changes from one user type to another: bike users in the Customer user type tend to use bikes for a longer period of time (around 20 minutes) than Subscriber user type (around 8 minutes). I believed it is linked to the type of contract or subscription that every user chose affecting their usage behaviour.

Secondly, the distribution of number of trips per hour shows a clear tendency of spikes during the commute hours (from 7:00-9:00 and 16:00-18:00) and very low activity during the night hours (23:00-5:00).

Finally, by using the columns of latitude and longitude, I was able to draw a cluster map and then come to a conclusion that for the cluster of San Francisco, the number of trips is very high in its downtown flat area (trips with low duration), and it gets lower and more time consuming on the city's outskirts, where people have to drive uphill and downhill to or from the downtown.

### Key Insights for Presentation

For the presentation, I focused the most on the trip duration variable and the geographical insights. I started by thoroughly analysing the trip duration variable and its relationship with other variables in the dataset. For this analysis, I mostly used various bar charts (horizontal and vertical).

Afterwards, in order to perform a thorough analysis on the geographical variables, I took to bivariate and multivariate explorations. The most successful way of communicating these data was by creating various heatmaps, sometimes using `subplot` function for better visualisations of certain trends. 

### Files used
I used the following files to accomplish the project:
* **README.md**;
* **ford.csv** - the database with all the trips' log data;
* **Project_Baywheels_Part1.ipynb** - Jupyter notebook containing **exploratory** visualisations;
* **Project_Baywheels_Part2.ipynb** - Jupyter notebook containing **explanatory** visualisations;
* **Project_Baywheels_Part1.html** - HTML version of the **exploratory** part;
* **Project_Baywheels_Part2.slides.html** - HTML (slide) version of the **explanatory** part;
* **output_toggle.tpl** - This file adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output.
Project;

### Credits
The **output_toggle.tpl** was downloaded from [damianavila's Github page](https://github.com/damianavila/blog/blob/master/posts/hide-the-input-cells-from-your-ipython-slides.ipynb)
Otherwise, during the preparation and the submission of the project, **no external source** was used during the submission.

Special thanks to the Udacity team for this project and its review!
