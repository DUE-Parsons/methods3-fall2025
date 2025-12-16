---
layout: project-page
title: "Block by Block: Hyperlocal Solidarities in Bed-Stuy"
linkname: block-by-block-hyperlocal-solidarities-in-bed-stuy
author: "Delaney Connor"
tagline: "Interactive maps connecting Bed-Stuy residents with block associations and community resources to strengthen neighborhood solidarity."
location:
    - place: Bed-Stuy, Brooklyn, New York City, USA
project-link:
    - href: https://delaneyconnor.github.io/block_associations/
tags:
    - tag: community organizing
    - tag:  gentrification
    - tag:  block associations
    - tag:  civic participation
    - tag:  solidarity
    - tag:  Brooklyn
    - tag:  geocoding
thumbnail-path: img/block-by-block-hyperlocal-solidarities-in-bed-stuy/qDpI2GO.png
img-folder: ../../img/block-by-block-hyperlocal-solidarities-in-bed-stuy/
timestamp: 12/14/2025 23:10:46
---
<hr style="border: 10px dashed #000000;">

## ▦ Introduction

The Bed-Stuy Community Maps project is an interactive mapping platform designed to strengthen civic participation and solidarity in Bedford-Stuyvesant, Brooklyn. This project emerges from my thesis research examining how block associations can foster cross-class, cross-cultural, and cross-generational solidarity in gentrifying/gentrified Bed-Stuy.

My final project is an online platform that contains two working maps: one that maps Bed Stuy Block Associations and another that maps Community Resources. This resource is a work in progress, with anticipated future features including an upcoming neighborhood block party map that will list permits filed in the [NYC Permitted Event Information](https://data.cityofnewyork.us/City-Government/NYC-Permitted-Event-Information/tvpp-9vvx/about_data) data set.

<hr style="border: 3px dashed #000000;">

![Figure 1: The landing page of the Bed-Stuy Community Maps platform]({{ page.img-folder }}7XHghve.png)

<hr style="border: 10px dashed #000000;">

## ▦ Partners

This map is a collaborative effort between the Crown Heights Care Collective and the Bed-Stuy Works Alliance of Block and Resident Associations. This work initially emerged from my personal desire to connect with my block association, but struggling to find an information hub with an updated list. The Community Boards are supposed to make this information public, but my board's website does not have an up to date list.

The Bed Stuy Works Alliance is an association of block associations. It was formed in 2010 by the Bridger Street Development Corporation. It convenes monthly, and hosts elected officials and community updates. They also organize annual giveaways of flowers for associations to bring back to their blocks. They historically attempted to produce an online map of associations in partnership with The Laundromat Project, but that project was not completed.

The Crown Heights CARE (Community Abolition Resources Education) Collective is an organizing body based out of Central Brooklyn's Crown Heights neighborhood, which is situated directly south of Bed Stuy. The CARE Collective has worked since early 2022 to bring neighbors together to take action. Their Root Work initiative directly supports ongoing power building within block associations. They have been working on their own block association map, blockmapper.org, listing associations through word of mouth.

Both groups are excited to produce an online map that helps residents connect with their block associations. This work will continue to grow and iterate alongside collaborative wisdom and insights gathered through our work directly with block associations.

![Figure 2: Community partners with whom this work supports]({{ page.img-folder }}USVZCsO.png)

<hr style="border: 10px dashed #000000;">

## ▦ The Data!

The foundation of this project is the [NYC Permitted Event Information - Historical](https://data.cityofnewyork.us/City-Government/NYC-Permitted-Event-Information-Historical/bkfu-528j/about_data) dataset. This dataset contains approved street closure event applications from 2008 onwards, including information about block parties and other community events across all five boroughs. It has a counterpart data set, [NYC Permitted Event Information](https://data.cityofnewyork.us/City-Government/NYC-Permitted-Event-Information/tvpp-9vvx/about_data) which lists all information on approved event applications that will occur within the next month.

### Dataset Columns

| Column Name | Description | Data Type |
|-------------------------|-------------------------|----------------------|
| Event ID | The event ID | Number |
| Event Name | The event name | Text |
| Start Date/Time | The start date/time of this event. For most events this will be the setup time (i.e. the date/time where the applicant has permission to begin closing the street or erecting components of the event) | Floating Timestamp |
| End Date/Time | The end date of this event. For most events this will be the breakdown time (i.e. the date/time where the applicant can still close the street or is dismantling/cleaning components of the event) | Floating Timestamp |
| Event Agency | The NYC agency that is considered the primary permitting agency for this event | Text |
| Event Type | The type of event | Text |
| Event Borough | The borough that the event will be held in | Text |
| Event Location | The location of the event | Text |
| Event Street Side | The side of the street that the event will be held on if the location is a street | Text |
| Street Closure Type | The type of street closure if the location is on a street | Text |
| Community Board | The Community Board where the event is located | Text |
| Police Precinct | The police precinct where the event is located | Text |

<hr style="border: 10px dashed #000000;">

## ▦ Visualizing  the Data

With this dataset in hand, I conducted several analyses to understand block party patterns, demographic shifts, and community organizing infrastructure across NYC and specifically in Bedford-Stuyvesant.

### Block Party Maps

Early explorations with this data set were focused on block party mapping. I wanted to learn where and when block parties occurred most in NYC. Limited by the specificity of the data set's shapefile or geometry, I could aggregate only according to community board or police precinct. 

I depicted the number of annual block parties hosted in each community board in 2010 and 2024. One of the most revealing aspects of this analysis was examining block party permits across NYC from 2010 to 2024. The data shows dramatic drops during the COVID-19 pandemic in 2020, followed by a strong recovery. Brooklyn consistently hosts the highest number of block parties, with certain community boards showing particularly active organizing traditions.

**2010**

![Figure 3: Block party permits by NYC community board, 2010]({{ page.img-folder }}CTnsKQU.png)

**2024**

![Figure 4: Block party permits by NYC community board, 2024]({{ page.img-folder }}bfSthAo.png)

<hr style="border: 3px dashed #000000;">

### Most Active Bed Stuy Blocks

![Figure 5: Top 15 recurring block party locations in Bed-Stuy (2010-2024)]({{ page.img-folder }}UOfMMSr.png)

<hr style="border: 3px dashed #000000;">

### Seasonal Patterns

![Figure 6: Block party frequency by month and year, showing seasonal trends]({{ page.img-folder }}4Cxj6lu.png)

<hr style="border: 3px dashed #000000;">

### Demographic Changes

To understand the gentrification context in which block parties operate, I mapped demographic shifts across NYC from 2011-2019. These maps reveal patterns of racial demographic change that coincide with rising housing costs and displacement pressures.

![Figure 7: Change in percentage of total white population, NYC 2011-2019]({{ page.img-folder }}YpHk8Gz.png)

<hr style="border: 3px dashed #000000;">

### Rent Increases

The change in rent prices from 2011 to 2019 shows particularly intense pressure in central Brooklyn neighborhoods, including Bedford-Stuyvesant. This economic data helps contextualize why community organizing and solidarity infrastructure are increasingly critical.

![Figure 8: Change in rent prices across NYC, 2011-2019]({{ page.img-folder }}tHF6xld.png)

<hr style="border: 3px dashed #000000;">

### Honorary Street Names

NYC's honorary street naming process represents another form of community organizing and cultural preservation. Mapping these honorary streets by community board reveals how different neighborhoods use this civic process to maintain cultural memory and recognize community leaders.

![Figure 9: NYC honorary street names by community board]({{ page.img-folder }}L9RCSr6.png)

<hr style="border: 3px dashed #000000;">

### 311 Street Noise Complaints

As a proxy for tension and conflict in gentrifying areas, I mapped 311 street noise complaints in Bedford-Stuyvesant from 2010-2024. The spatial distribution of these complaints can indicate friction between longtime residents and newcomers, or areas experiencing particular development pressure.

![Figure 10: Bed-Stuy 311 street noise complaints, 2010-2024]({{ page.img-folder }}xTWEv8R.png)

<hr style="border: 10px dashed #000000;">

## ▦ Technical Implementation

One of the significant technical challenges was geocoding the [NYC Permitted Event Information - Historical](https://data.cityofnewyork.us/City-Government/NYC-Permitted-Event-Information-Historical/bkfu-528j/about_data) dataset. Working with Eric, we developed a Python script to match event location strings with NYC's street centerline data. This required handling inconsistent formatting, abbreviations, and edge cases as well.

The geocoding process achieved approximately 75% success rate initially, and after honing the script, 95% success.

![Figure 11: Geocoding formula]({{ page.img-folder }}phyw7d6.png)

I was able to test out the geocoding in Bed-Stuy only, because of the immense labor to process the failures. This allowed me to produce a graduated map of block party frequency in Bed Stuy, showing frequency by line thickness.

![Figure 12: Block party frequency in Bed-Stuy by street segment]({{ page.img-folder }}QxAMIhL.png)

<hr style="border: 10px dashed #000000;">

## ▦ The Community Map Platform

### Web Development

I built the interactive map using HTML, CSS, and JavaScript with Mapbox GL JS for the mapping functionality. The codebase includes custom styling to make the interface accessible and welcoming to community members who may not be familiar with digital mapping tools.

![Figure 13: Sample code from VS Code]({{ page.img-folder }}1NPbEQP.png)

<hr style="border: 3px dashed #000000;">


### Block Mapper Interface

The final platform centers on an interactive "Block Mapper" that allows Bed-Stuy residents to search for block associations near their address. Users can explore the map, click on markers to learn about different organizations, and access resources for starting their own block association.

<a href="https://delaneyconnor.github.io/block_associations/" target="_blank" style="display: inline-block; padding: 12px 24px; background-color: #000000; color: #ffffff; text-decoration: none; border-radius: 5px; font-weight: bold; margin: 20px 0;">Explore the Live Map</a>

![Figure 14: Block association map interface]({{ page.img-folder }}69TrqcP.png)

![Figure 15: Community resources map interface]({{ page.img-folder }}6E1v8N8.png)

<hr style="border: 10px dashed #000000;">

## ▦ Future Development

The roadmap for this project includes several key features:

**Immediate priorities:**

* Adding a comprehensive block party map with geocoded upcoming street closure data

* Discovering more NYC neighborhood block associations through their block parties hosted

* Populating the block associations database with verified contact information

**Medium-term goals:**

* Collecting and archiving oral histories from longtime block association organizers

* Creating a start-up guide for new block associations

* Adding meeting facilitation resources

* Mapping political representative districts with contact information

<hr style="border: 10px dashed #000000;">

## ▦ Reflection

This project represents an attempt to use data vis and mapping to produce a tool that is of use to the community from where my research emerges. By making information about block associations accessible and visible, I hope to support the organizing work already happening in Bedford-Stuyvesant and inspire new neighbors to participate in democratic, hyperlocal governance. The technical challenges—from data cleaning to geocoding to web development—were substantial. Moving forward, the success of this platform will depend on continued collaboration with community organizations and responsiveness to what residents actually need.

<hr style="border: 10px dashed #000000;">

## ▦ Data Visualizations: Methodology

### Figures 3 & 4: Block Party Permits by Community Board

**Data source:** [NYC Permitted Event Information - Historical](https://data.cityofnewyork.us/City-Government/NYC-Permitted-Event-Information-Historical/bkfu-528j/about_data), NYC Open Data

**Analysis:** These maps visualize NYC street permit data, specifically permits issued for block parties in 2010 and 2024. Using R Studio, I organized the data by community board and produced a count for each. I then imported the resulting CSV into QGIS, where I joined it to the community board shapefile data and created a choropleth shading system according to the number of block parties in each community board. I organized the choropleth in equal distribution buckets along a greyscale color gradient, using the same scale and coloring on both maps for ease of comparison.

**Results:** The comparison reveals significant geographic variation in block party permits, with Brooklyn—particularly central Brooklyn community boards—showing the highest concentrations. The data shows a clear decrease in block party permits over the 14 years between 2010 and 2024, with the 2024 map demonstrating recovery from pandemic-era lows, though some neighborhoods show shifting patterns of community organizing.

### Figure 5: Most Active Block Party Locations

**Data source:** [NYC Permitted Event Information - Historical](https://data.cityofnewyork.us/City-Government/NYC-Permitted-Event-Information-Historical/bkfu-528j/about_data), NYC Open Data

**Analysis:** Event location strings were parsed and deduplicated to identify blocks with recurring block parties over the 2010-2024 period. The top 15 locations were ranked by frequency of events.

**Results:** The data reveals strong traditions of annual block party organizing on specific streets in Bed-Stuy, with some blocks hosting events 15-19 times over the study period. This suggests sustained community organizing capacity and stable residential populations in these locations.

### Figure 6: Seasonal Patterns

**Data source:** [NYC Permitted Event Information - Historical](https://data.cityofnewyork.us/City-Government/NYC-Permitted-Event-Information-Historical/bkfu-528j/about_data), NYC Open Data

**Analysis:** Block party permits were aggregated by month and year to identify seasonal trends. A heatmap visualization was created to show the intensity of block party activity across different months and years.

**Results:** Block parties show strong seasonality, concentrated in summer months (June-September), with August showing peak activity. The dramatic reduction in 2020 reflects COVID-19 restrictions, while 2021-2024 show gradual recovery toward pre-pandemic levels.

### Figures 7 & 8: Demographic and Rent Changes

**Data source:** U.S. Census Bureau, American Community Survey 5-Year Estimates (2011-2015, 2015-2019)

**Analysis:** I used an R Studio script to pull in data from the ACS 2005, 2011, and 2019 datasets and then brought that into QGIS to join with spatial data to produce the maps. I specifically wanted to produce maps that could explain various contributing factors of gentrification, such as an influx of white residents to areas over time and changes in median income level. Census tract-level data was analyzed to calculate percentage change in white population and median rent prices between 2011 and 2019. Data was mapped using census tract boundaries and visualized with diverging color scales.

**Results:** The maps reveal patterns of demographic change consistent with gentrification, particularly in central Brooklyn neighborhoods including Bedford-Stuyvesant. Areas showing increased white population percentages correlate strongly with areas experiencing the highest rent increases.

### Figure 9: Honorary Street Names

**Data source:** [NYC Honorary Street Names Map](https://data.cityofnewyork.us/), NYC Open Data

**Analysis:** I created this map by downloading shapefiles of NYC street centerlines, community board boundaries, and honorary street centerlines from NYC Open Data. I then intersected the street and honorary street centerlines with the community board polygons and added a new column to calculate the length of each street segment in feet and miles. Afterward, I summarized the data by community board to show how many feet and miles of each street type exist within each area. I also used a column from the street centerlines dataset that categorizes street types to compare which types of streets are most often renamed. The choropleth layer shows the percentage of each community board's total street surface area that has been renamed.

**Results:** The distribution of honorary street names varies significantly across community boards, with some neighborhoods using this civic tool more actively for cultural preservation and community recognition. The map reveals how different neighborhoods use this process to maintain cultural memory and recognize community leaders.

### Figure 10: 311 Noise Complaints

**Data source:** [311 Service Requests](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9), NYC Open Data

**Analysis:** I worked with NYC 311 data from 2010 to 2024, filtering for complaints made in Bed-Stuy that were tagged as occurring in the "Street." Street noise complaints were filtered for Bedford-Stuyvesant neighborhood boundaries and mapped at the address level using heatmap visualization. I adjusted the heatmap settings to best visualize density across the neighborhood.

**Results:** The spatial distribution of noise complaints shows clustering, potentially indicating friction between residents. The resulting map highlights areas of consistently high complaint activity.

<hr style="border: 10px dashed #000000;">

## ▦ Acknowledgments

Special thanks to Eric for collaboration on the geocoding script and everything else, the Bed-Stuy Works Alliance and Crown Heights CARE Collective for their partnership, and the community members who have contributed to making this resource useful. Contact delaneyconnor1@gmail.com with any questions!
