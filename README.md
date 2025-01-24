# GitHub Template For Reproducible Research 

## Overview
This repository sets out the skeleton of an organisational structure used for scientific research.

## How to Use
Clone the repository and restructure as necessary.

```
> git clone git@github.com:bchanlee/reproducible_research.git
```

Write a single text file (e.g. notes.txt) detailing everything

```
Key:
[ ] TODO
{ } TODO later
* important
# dates
## subheading
~ location
<> paper
https:// url
```
## Layout

### **`data`** 
All raw data collected from your experiments as well as copies of the transformed data from your processing/analysis code.

### **`experiments`** 
Where all of the experimental information lives, including any *executed* code. lives. This includes pipelines, scripts, and figure files. 
 * **`exploratory`**: A sandbox where you keep a record of your different approaches to transformation, interpretation, cleaning, or generation of data.
 * **`processing`**: Any code used to *transform* the data into another type should live here. This can include everything from parsing of text data, image segmentation/filtering, or simulations.
 * **`analysis`**: Any code to to *draw conclusions* from an experiment or data set. This may include regression, dimensionality reduction, or calculation of various quantities.
 * **`figures`**: Any code used to generate figures for your finished work, presentations, or for any other use. Also contains the figures themselves.