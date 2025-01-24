# Git + GitHub As A Platform For Reproducible Research 

## Overview
This repository sets out the skeleton of an organizational structure used for scientific research. It loosely follows what I have used for several of my research projects and I hope it inspires you to conduct your research in an open, reproducible, and honest manner.

## How to Use
Clone the repository and restructure as necessary.

```
> git clone git@github.com:bchanlee/reproducible_research.git
```

Write a single text file (e.g. notes.txt) detailing all experiments with Key

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

The repository is split into seven main directories, many of which have subdirectories. This structure has been designed to be easily navigable by humans and computers alike, allowing for rapid location of specific files and instructions. Within each directory is a `README.md` file which summarizes the purpose of that directory as well as some examples where necessary. This structure may not be perfect for your intended us and may need to be modified. Each section is briefly described below. 

### **`experiments`** 
Where all of the experimental information lives, including any *executed* code. lives. This includes pipelines, scripts, and figure files. 
 * **`exploratory`**: A sandbox where you keep a record of your different approaches to transformation, interpretation, cleaning, or generation of data.
 * **`processing`**: Any code used to *transform* the data into another type should live here. This can include everything from parsing of text data, image segmentation/filtering, or simulations.
 * **`analysis`**: Any code to to *draw conclusions* from an experiment or data set. This may include regression, dimensionality reduction, or calculation of various quantities.
 * **`figures`**: Any code used to generate figures for your finished work, presentations, or for any other use. Also contains the figures themselves

### **`data`** 
All raw data collected from your experiments as well as copies of the transformed data from your processing/analysis code.