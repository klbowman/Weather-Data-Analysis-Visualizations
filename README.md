# python-api-challenge
![image](https://user-images.githubusercontent.com/74067302/134268056-0916a403-a4c2-42ed-afa1-647a0737a419.png)

# Weather Data Visualizations & Maps

Weather data analysis and visualization using charts and interactive maps.

## Description

This repository is designed to visualize taxonomic data using charts, and display metadata in an organized panel. The [data](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/) comes from a study that sequenced the microbiome of 153 human belly buttons (Hulcr et al., 2012), and is stored in the samples.json file. Individual samples are identified by a numerical code and accompanied by metadata including age, gender, ethnicity, etc. Operational taxonomic units (OTUs) id numbers and counts are provided for each sample.

The dashboard includes a drop-down menu that displays the numerical code for each individual sample. When a sample is selected, the “Demographic Info” panel is populated with metadata and the following three charts are populated with data:
* Bar graph displaying the top 10 OTUs by count
* Gauge plot showing the belly button scrubs per week
* Bubble plot displaying OTU counts for the entire sample

<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/145615550-98e49162-44c9-4e39-9050-ba837dc42863.png" alt="Dashboard Image"/>
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/145615561-5fc19f35-646b-47aa-9f63-4a93a495efe5.png" alt="Dashboard Image"/>
</p>

## Getting Started

### Technologies Used 

* JavaScript
* HTML
* CSS

### Installing

* Clone this repository to your desktop.
* Navitage to the home directory and open index.html in your browser.

### Data Sources

* OpenWeatherMap API [Access Data](https://openweathermap.org/api)
* Google Places API [Access Data](https://developers.google.com/maps/documentation/places/web-service/overview)


## Authors

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)

