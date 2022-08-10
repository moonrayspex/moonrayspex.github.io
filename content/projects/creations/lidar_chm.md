---
title: "Modelling Canopy Height Model with LiDAR and Photogrammetric-derived Point Clouds"
date: 2022-07-22T22:25:14-04:00    
featured: true
description: "Using point cloud data to create a DTM and a DSM in order to calculate canopy height model."
tags: ["remote sensing","LiDAR","DSM", "DTM", "PCI Geomatica / Catalyst"]
image: "/img/LiDAR1.jpg"

fact: ""
weight: 500
sitemap:
  priority : 0.8
---


Imagery derived from elevation classified photogrammetric-derived elevation point cloud layer.  
Source image from Ontario GeoHub of a 1 square kilometer area near Bailieboro, Ontario. 
Image initially overlayed on standard false colour composite of an orthophotographic image of the same area from 2013 (not shown).

Figure 1. Below: Bailieboro LiDAR (sensor and date of acquisition) DSM (Digital Surface Model) shown in shaded relief.  
DSM derived from elevation point cloud layer. 
Forest, hedge rows and powerlines are prominent.
![LiDAR digital surface model](/img/LiDAR1.jpg "LiDAR Digital Surface Model")


Figure 2. Below: Bailieboro LiDAR DTM (Digital Terrain Model) shown in shaded relief.  
DTM derived from elevation point cloud layer.   
DTM depicts terrain undulations with the absence of surface vegetation and human structures.
![LiDAR Digital terrain model](/img/LiDAR_dtm.jpg "LiDAR Digital Terrain Model")



Figure 3. Below: Bailieboro LiDAR CHM (Canopy Height Model) using Jenks classification.  
CHM is the result of subtracting the DTM from the DSM.  
Areas of colour depict vegetation heights; areas absence of colour have little to no vegetative height. 
Areas with highest CHM are red and a decrease in height corresponds with colour shift to orange, yellow, light green, respectively. 
Note, power lines are present in this model due to their height.  

![LiDAR crown height model](/img/LiDAR_CHM.png "LiDAR Crown Height Model")

