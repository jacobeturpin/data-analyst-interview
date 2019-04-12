# Data Analyst Interview Project
Provided directions to the data analysis project as part of the data analyst interview process

## Introduction
The following is an outline for a simple data analysis project. It is being assigned as part of the interview for the Data Analyst position at ConnectWise, Inc.

The aim of this test is to assess your overall preparedness for typical tasks that will be necessary to perform as part of a data science team. The project was designed to have an anticipated completion time of 60-90 minutes for an entry-level data analyst.

## Rules

* Unless explicitly stated, please provide your analysis through code or comments.
* You are free to use whatever language and environment desired to complete this task. We promise this isn't a trick; use the language you're most comfortable with using. The only expectation is that we will be able to recreate your work from your provided code. Please provide any enviornment files (requirements.txt, package.json, etc.) in your completed analysis. If such tools are available in your language of choice, consider using an interactive environment like a Jupyter Notebooks.
* Submissions for this project will only be accepted and considered by applicants that have been specifically requested to do so.

## Submission
Once complete, please send a link to your repository to [sresar@connectwise.com](mailto:sresar@connectwise.com).

## Directions

1. Fork this repository to create a new working copy for your submission.
1. To conduct your analysis, we have provided a dataset for download [here](https://s3.amazonaws.com/cc-analytics-datasets/Building_Permits.csv). The provided dataset comes from the City of Raleigh Open Data website and is based upon pending/granted building permits. Documentation on the dataset can be found [here](http://data-ral.opendata.arcgis.com/datasets/building-permits).
1. Load the data from the provided source via a web request rather than downloading a local copy and loading from disk.
1. Review the summary statistics for the included features. Please be sure to include the following in your exploratory data analysis:
   - Number of rows and columns in the dataset
   - Total different types of construction
   - Mean and median number of stories
   - Standard deviation for the X and Y coordinates of the permits
1. Plot the distributions for each of the following features: _Estimated Project Cost_ and _Issue Date Month_. Describe the distributions for these fields and explain what insights you might be able to gather.
1. A hypothetical executive team is interested in the behavior between _Permit Issue Year_ and _Estimated Project Cost_, but only for the "New" construction work class, with a construction type of "V  B", and with less than 3 stories. Perform a simple regression analysis of this relationship and describe what insights we can gleam from this using success metrics. _(Hint: Implement handling for missing values and explain your reasoning.)_ 
1. Commit all changes and analysis, then email your completed submission.
