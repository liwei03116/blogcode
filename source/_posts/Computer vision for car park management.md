---
title: Computer vision for car park management
date: 2023-11-28 18:06:54
categories:
  - Image Processing
tags:
  - IT
  - AI
  - Coding
  - Web
---

## Why Use Computer Vision for Car Parks?

Car park zones need to detect the number of occupied parking spaces. The management system can show the potential empty slots for drivers looking to park in the zone. Computer vision can accurately determine the number of occupied spaces in a car park zone.

<!--more-->

## What Is the Recent Solution?

Currently, car park zones use a multitude of sensors, with each parking slot equipped with its own sensor. However, this approach requires a substantial budget to purchase and install numerous sensors. An alternative and more economical solution involves using a few webcams strategically placed to cover the entire area of the zone.

## What Technical Stack Should Be Used?

OpenCV is one of the best solutions for implementing computer vision. In the initial step, a detection area can be defined, typically using rectangles. Subsequently, the system should display the Region of Interest (ROI) value, indicating changes in the scene compared to an empty slot. For increased accuracy, Canny edge detection can be implemented, as it effectively detects object shapes.

## Outcome

This application has been implemented in the industry, and the feedback indicates that the system significantly reduces costs associated with parking space monitoring in car park areas.

## Demo video

https://www.youtube.com/watch?v=ZITggtxuYA8
