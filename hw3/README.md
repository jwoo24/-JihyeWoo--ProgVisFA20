[Week4] Homework 3
===
Build SVG Paths using my own data
---

The attached visualization is an SVG path that shows the number of steps I walked last week from September 14 to 20, 2020.
A sneaker's shape path represents my steps. The more I walked, the darker the red color appears. In this homework, I successfully loaded data from a CSV file.

Here is an image of how that displays.

- Updated on Sep 29, 2020: 
Used d3.scaleSequential function for this version. 
```
d3.scaleSequential()
.domain([minData,maxData])
.interpolator(d3.interpolateOrRd);
```
<img src="https://github.com/jwoo24/JihyeWoo-ProgVisFA20/blob/master/hw3/hw3_screenshot_update_0929.png?raw=true">

- Updated on Sep 28, 2020

<img src="https://github.com/jwoo24/JihyeWoo-ProgVisFA20/blob/master/hw3/hw3_screenshot_update_0928.png?raw=true">

- Originally Created on Sep 21, 2020
<img src="https://github.com/jwoo24/JihyeWoo-ProgVisFA20/blob/master/hw3/hw3_screenshot.png?raw=true">
