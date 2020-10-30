---
layout:      project
title:       "Self-Organizing Maps"
date:        3 Sep 2019
image:
  path:       assets/img/Polk_Seasons.png
 # srcset:
    #1920w:   /assets/img/blog/blog/hydejack-8.jpg
   # 960w:    /assets/img/blog/blog/hydejack-8.jpg
   # 480w:    /assets/img/blog/blog/hydejack-8.jpg
caption:     Clustering analysis on the temporal characteristics of car crashes.
description: >
  Vehicle crashes happen every minute in the United States, each crash having its own time and specific attributes such as road conditions and weather. The goal of this project is to find meaningful spatial and temporal patterns from the large datasets provided by state DOT’s. Using a self-organizing map, data can be clustered into meaningful clusters based on time of year, month, or day in a way that is easy to read. This allows for a more in-depth analysis. Data can then be joined to point data in ArcMap to show how patterns relate spatially within certain attributes like road conditions, number of injuries or weather conditions. The significance of this is that it allows temporal data to be joined to spatial data. This allows for multifaceted in-depth analysis. 

  In this project our group analyzed the spatial and temporal characteristicts of vehichle cr
  

links:
  - title:   Github Link
    url:     https://github.com/SapirLastimoza-Dooley/self_organizing_maps
featured:    true
---
# Self-Organizing Maps

## Summary
* Project Lead: Shuyang Zhang
* Project Members: Arielle Wood, Gabriel Ibiassi Nambila, Luke Anderton, Sapir Carlo Dooley
* Data Source: IOWA Department of Transportation
* Programs Used: ArcPro, Visual Studio Code
* Languages Used: Python- ArcPy, sompy, mathplotlib, numpy, sklearn, multiprocessing, neighborhood, normalization
* Outcomes: Maps, Heatmaps, Charts

## Outcomes
![Crash Distribution](https://raw.githubusercontent.com/SapirLastimoza-Dooley/self_organizing_maps/main/figures/crash_distribution.png){:.lead width="864px" height="667.86px" loading="lazy"}

Fig. 1: Spatial distribution of car crashes in Polk County and Scott County, IA (2011-2016).
{:.figcaption}

![Monthly Heatmap](https://raw.githubusercontent.com/SapirLastimoza-Dooley/self_organizing_maps/main/figures/year_heatmap.png){:width="282px" height="431px" loading="lazy" style="float: left"}
Clustering Heatmap of car crashes monthly in Polk County (2013)

![Monthly Distribution](https://raw.githubusercontent.com/SapirLastimoza-Dooley/self_organizing_maps/main/figures/monthly_distribution.png) 
![Cluster Hitmap](https://raw.githubusercontent.com/SapirLastimoza-Dooley/self_organizing_maps/main/figures/clustering_heatmap_1.png)


Fig. 2(a): Clustering Heatmap of car crashes monthly in Polk County (2013); (b): Monthly distribution of all car crashes in Polk County (2011-2016); (c): Hitmap for clustered data in Polk County.
{:.figcaption}: 

![Weekly Heatmap](https://raw.githubusercontent.com/SapirLastimoza-Dooley/self_organizing_maps/main/figures/week_heatmap.png)

Fig. 3(a): Clustering Heatmap of car crashes monthly in Polk County (2013).
{:.figcaption}
