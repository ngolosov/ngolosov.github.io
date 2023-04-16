---
layout: project
type: project
image: img/purpleair/purpleair1.PNG
title: "PurpleAir data downloader plug-in for QGIS"
date: 2021
published: true
labels:
  - Python
  - QGIS
  - Multi-processing
  - Concurent futures
summary: "A QGIS plugin to download air quality data from PurpleAir crowdsourced monitoring website."
---

<p>I developed a QGIS plugin to download historical air quality data from the PurpleAir website, using its API. The tool requests a list of sensors and their coordinates within a requested bounding box, and downloads historical data for each sensor within a specified timeframe. It calculates averages for that historical data, and creates a point layer with sensor locations and average pollution attributes, which is added to the map. I used the Requests library to retrieve JSON data, concurrent futures library to retrieve multiple JSON files simultaneously, Pandas to calculate averages, and PyQT5 and QGIS to provide the user with a GUI. The plugin is user-friendly and reusable.</p>

<a href = "https://github.com/ngolosov/PurpleAirDownloader" class="btn btn-outline-dark">View on GitHub</a>

## Screenshots (click to enlarge):

<div class="text-center p-4">
   <a href="../img/purpleair/purpleair1.PNG"> <img width="200px" src="../img/purpleair/purpleair1.PNG" class="img-thumbnail" ></a>
</div>
