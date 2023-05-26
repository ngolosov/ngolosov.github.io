---
layout: project
type: project
image: img/panoramic-tools/pt1.png
title: "DIY Streetview Tools for Krpano Panoramic Viewer"
date: 2023
published: true
labels:
  - Python
  - GeoPandas
  - PyQT5
  - Hugin tools
summary: "This project implements Python tools for linking panoramic images into a self-hosted virtual tour, a-la Google Streetview using self-hosted Krpano panoramic viewer. These tools allow you to create a custom Streetview-like experience by connecting and displaying your panoramic images."
---

<p>I have developed two Python tools and a GUI for them using PyQt5 to create self-hosted virtual tours, similar to Google Street View, where users can navigate between linked panoramic views. There are two scripts - `convert_panoramas.py` and `visualize_connections.py`.</p>
<p>
`convert_panoramas.py` performs geometric correction on the input panoramic images using the embedded compass and gyro information from the image XMP tags, utilizing the Nona application from the Hugin tools. Additionally, it creates a point shapefile representing the locations of the input panoramic images.</p>
<p>
The second script, `visualize_connections.py`, links the spherical panoramas to one another by finding the nearest neighbors within a specified search radius or by using a line shapefile representing links between panoramas. Users can create these links in GIS software such as QGIS.</p>

<a href = "https://github.com/ngolosov/PanoramicTools/" class="btn btn-outline-dark">View on GitHub</a>
<a href = "https://github.com/ngolosov/PanoramicTools/releases/download/PanoramicTools/Panoramic_tools_v0.1.zip" class="btn btn-outline-dark">Download Windows binaries</a>

## Screenshots (click to enlarge):

<div class="text-center p-4">
   <a href="../img/panoramic-tools/pt3.png"> <img width="200px" src="../img/panoramic-tools/pt3.png" class="img-thumbnail" ></a>
   <a href="../img/panoramic-tools/pt4.png"> <img width="200px" src="../img/panoramic-tools/pt4.png" class="img-thumbnail" ></a>
   <a href="../img/panoramic-tools/pt2.png"> <img width="200px" src="../img/panoramic-tools/pt2.png" class="img-thumbnail" ></a>
</div>
