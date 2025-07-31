# EDS 296 Final Project: Climate Projection Over the Hawaiian Islands
### Madison Enda, Bailey Jorgensen, Michelle Yiv 
### 06/10/2025

## Introduction

We chose to analyze how climate change is projected to impact the Hawaiian Islands. In the past few decades, Hawaii has tried hard to curtail the ill effects of harmful algal blooms on its more populated islands, like Oahu and Maui. These HABS events, the result of increased water pollution and Hawaii's naturally warm climate, destroy the coral reefs that protect the islands from wave/storm damage and flooding.

With the looming threat of climate change, we wondered whether or not temperatures would increase dramatically enough in the equatorial region to incite more algal blooms or generally become too warm for reef building coral in the coming decades.

![Hawaii. Source: seatemperatu.re](https://www.seatemperatu.re/site/images/illustration/hawai_642.jpg) 


## Metrics Definition:

All of our data came from CMIP6 catalog currently hosted by Amazon. For our climate scenarios, we chose to use all the years available for our historic simulations, as well as all the data available for future projection ssp370. We chose a predicted emissions scenario between the higher possible projections (ssp585) and the lower possible projections (ssp126) for a conservative yet realistic estimate. In ssp370, we predict additional radiative force of about 7 W/m² by the year 2100.

For our models, we chose CESM2 and CanESM5, both models that we knew to have solid coverage of our region, and that had worked well in similar analysis in the past. For the final analysis, we used ACCESS-CM2, as the aforementioned models had a great deal more ensemble members, that were too computationally intensive to work with.

The variables we chose to look at were near-surface air temperature (tas), precipitation (pr), and near-surface shortwave radiation (rsds). We believed air temperature would be a good indication of overall temperature trends on both land and in the water, that precipitation would be indicative of runoff volume, and that radiation would tell us more about cloud cover and clue us in to specific trends between land and sea.

![Hawaii Map. Source: mauihawaii.org](https://www.mauihawaii.org/wp-content/uploads/2021/12/hawaii-map-feature.jpg) 
