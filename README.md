# Workshops
Notes, scripts, and exercises for data science workshops put on through ECOSCOPE (http://ecoscope.ubc.ca/)

## The data
The data in these workshops were collected as part of an on-going oceanographic time series program in Saanich Inlet, a seasonally anoxic fjord on the East coast of Vancouver Island, British Columbia (Figure 1). We use data from various geochemical measurements at many depths in Saanich Inlet over time (approximately monthly from 2006 to 2014) as well as microbial data from selected time frames and depths of interest.

![](https://github.com/EDUCE-UBC/workshops/blob/master/images/Saanich.png){width=4in}

**Figure 1.** Map of Saanich Inlet indicating conventional sample collection stations (S1-S9). Data used in this workshop is sourced from S3.

Saanich Inlet is a steep sided fjord characterized by a shallow glacial sill located at the mouth of the inlet that restricts circulation in basin waters below 100 m (Figure 2).

![](https://github.com/EDUCE-UBC/workshops/blob/master/images/Inlet_structure.png)

**Figure 2.** Structure of Saanich Inlet. The glacial sill restricts water circulation into and out of the lower depth of the inlet basin.

During spring and summer months, elevated primary production (like photosynthesis) in surface waters combined with restricted circulation results in progressive water column stratification and complete oxygen starvation (anoxia) in deep basin waters. In late summer, pulses of oxygenated nutrient-rich ocean waters upwelling from the Haro Straight cascade over the sill, displacing oxygen starved bottom waters upward. The intensity of these renewal events varies from year to year with implications for microbial ecology and biogeochemical cycles (Figure 3). 

![](https://github.com/EDUCE-UBC/workshops/blob/master/images/oxygen_timeseries.png)

**Figure 3.** Contour plot of water column oxygen concentrations over multiple years in the time series. Warmer colors indicate high oxygen concentrations while cooler colors are low. Note the recurring pattern of oxygen decline below 100 m depth intervals followed by seasonal renewal events in late Summer into early Fall carrying more oxygenated waters into the Inlet. 

The seasonal cycle of stratification and deep water renewal enables spatial and temporal profiling across a wide range of water column energy states and nutrients, thus making Saanich Inlet a model ecosystem for studying microbial community responses to ocean deoxygenation. Ocean deoxygenation is a widespread phenomenon currently increasing due to climate change. 

For a brief introduction to the data, see Hallam SJ *et al*. 2017. Monitoring microbial responses to ocean deoxygenation in a model oxygen minimum zone. Sci Data 4: 170158 [doi:10.1038/sdata.2017.158](https://www.nature.com/articles/sdata2017158) More detailed information on the geochmeical data can be found in Torres-Beltrán M *et al*. 2017. A compendium of geochemical information from the Saanich Inlet water column. Sci Data 4: 170159. [doi:10.1038/sdata.2017.159](https://www.nature.com/articles/sdata2017159) More detailed information on the mutli-omic microbial data can be found in Hawley AK *et al*. 2017. A compendium of multi-omic sequence information from the Saanich Inlet water column. Sci Data 4: 170160. [doi:10.1038/sdata.2017.160](https://www.nature.com/articles/sdata2017160)



## Introduction to R and RStudio
Coming soon!


## Introduction to the tidyverse
In this workshop, we provide a brief introduction to RStudio, then delve into data manipulation and graphics in the tidyverse including the packages dplyr, tidyr, and ggplot2. We teach different ways to manipulate data in tabular and text forms as well as the critical concepts underlying the grammar of graphics and how they are implemented in ggplot. We will use RStudio, a powerful but user-friendly R environment, and teach you how to use it effectively.

You will learn how to :

* create an R project and import data from a file into R,
* create subsets of rows or columns from data frames using dplyr,
* select pieces of an object by indexing using element names or position,
* change your data frames between wide and narrow formats,
* create various types of graphics,
* modify the various features of a graphic, and
* save your graphic in various formats

## Reproducible research in R and Git
Coming soon!

## Statistical models in R
Coming soon!
