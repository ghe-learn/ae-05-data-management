# ae-05-data-management

This repository is an application exercise, which was developed for the following course: https://rbtl-fs22.github.io/website/. It is part of an assignment that is used for lecture week 5 on Tools for Data Collection and Data Management.

The structure for the attributes table was taken from the R package: [{dataspice}](https://github.com/ropensci/dataspice), which follows [schema.org](https://schema.org/) standards.

# directories

## /data

This directory contains the following files:

**`attributes.csv`**  

A template CSV file for attributes of datasets contained in this folder. The file has the following attributes itself: 

| variableName | description                                             |
|--------------|---------------------------------------------------------|
| fileName     | the name of the input data file(s)                      |
| variableName | the name of the measured variable                       |
| description  | a written description of what that measured variable is |
| unitText     | the units the variable was measured in                  |
| variableType | the variable data type                                  |

**README.md**

A [markdown template](https://cornell.app.box.com/v/ReadmeTemplate) adapted from a [guide shared by Cornell University](https://data.research.cornell.edu/content/readme) and recommended for use by ETH Library under [Guidance and instructions for the ETH Zurich DMP template - Section 1: Data collection and documentation - 1.3 What documentation and metadata will you provide with the data? - Supporting resources](https://documentation.library.ethz.ch/display/DD/Data+Management+Plan+Instructions+for+ETH+Zurich+Researchers). 

## /img

Images used in `ae-05-data-management-exercises.Rmd`. 

