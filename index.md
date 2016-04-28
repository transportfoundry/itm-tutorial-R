---
layout: lesson
root: .
lastupdated: 28 April 2016
contributors: ["Josie Kressner", "Greg Macfarlane", "Sarah Supp", "John Blischak","Gavin Simpson","Tracy Teal","Greg Wilson","Diego Barneche"," Stephen Turner","Francois Michonneau"]
maintainers: ["Josie Kressner", "Greg Macfarlane"]
domain: Transportation
topic: R for data analysis
software: R
status: Teaching
---

# Data analysis and visualization in R for transportation

Data Carpentry's aim is to teach researchers basic concepts, skills,
and tools for working with data so that they can get more done in less
time, and with less pain. The lessons below were designed for those interested
in working with {{page.domain %}} data in {{page.topic %}}.

This is an introduction to R designed for participants with no programming
experience. These lessons can be taught in an hour and a half tutorial. They start with some
basic information about R syntax, the RStudio interface, and move through how to
import CSV files, the structure of data.frame, how to deal with factors, how to
add/remove rows and columns, and finish with how to calculate summary statistics
for each level and a very brief introduction to plotting. Normal Data Carpentry
tutorials are taught over a day. This material is signficantly shortened.


**Content Contributors: {{page.contributors | join: ', ' %}}**


**Lesson Maintainers: {{page.maintainers | join: ', ' %}}**


**Lesson status: {{ page.status }}**

<!--
  [Information on Lesson Status Categories]()
-->

<!-- ###### INDEX OF LESSONS ON THIS TOPIC ###### -->

## Lessons:
1. [Lesson 00 Before we start](00-before-we-start.html)
2. [Lesson 01 Introduction to R and dplyr](01-new-intro-R.html)
3. [Lesson 02 Data visualization with ggplot2](02-visualization-ggplot2.html)
4. [Lesson 03 Using censusr](03-censusr.html) [bonus if time allows]

## Data
Two data files are required for this lesson: [nhts_day.csv](http://psrc.github.io/itm-tutorial-R/data/nhts_day.csv) and [nhts_per.csv](http://psrc.github.io/itm-tutorial-R/data/nhts_per.csv). These only include the first 200 lines of the full National Household Travel Survey files.

## Requirements
Data Carpentry's teaching is hands-on, so participants are encouraged to use
their own computers to insure the proper setup of tools for an efficient workflow.
*These lessons assume no prior knowledge of the skills or tools*, but working
through this lesson requires working copies of the software described below.
To most effectively use these materials, please make sure to install everything
*before* working through this lesson.

Please visit the ITM Tutorial [homepage](http://psrc.github.io/itm-tutorial-2016) for software installations instructions for Windows, Mac, and Linux.
