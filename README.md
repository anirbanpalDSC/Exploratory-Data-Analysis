# Exploratory-Data-Analysis

> Readme file for the Exploratory Data Analysis project

<img src="Images/EDA.png" data-canonical-src="Images/EDA.png" width="200" height="200" />

**Statistical/Hypothetical Question:**
Identify variables that are significant in driving the price of used cars in the used cars dataset from eBay.

**Outcome of the EDA:**
Strong relationships exist between certain variables but there are too many confounding factors to infer causation.  We are able to see strong relationship between car price and other factors like power of the engine, number of years old and number of days listed online.

**What do I feel was missed during the analysis?**
If I had another data set with enough data and the actual selling price of the cars, I could use the existing dataset to train the model and use the dataset with actual selling price to validate and predict on. With only listed price in the data, we can not do much other than exploratory data analysis.

**Were there any variables I felt could have helped in the analysis?**
If I could see actual selling price of the cars it would add our ability to validate and test our model.

**Were there any assumptions made you felt were incorrect?**
I assumed that factors like the car’s odometer reading (kilometer), model or brand will play a significant role in the price. I did not see the correlation as much as I expected. Also, having 10014 records with 0 price and having a maximum price value of 2147483647 in the data means even after the data cleansing, there were junk data left behind.

**What challenges did you face, what did you not fully understand?**
I understood and was able to apply Python in the different statistical calculations in the ask, such as PMF, CDF, Analytical Distribution, Hypothesis Testing, Regression Analysis, etc.  I developed a fair idea of how to slice and dice an unknown dataset to understand the internal dynamics. This dataset from Kaggle has helped me to easily apply the theoretical concepts in real world.

# Table of contents

- [Getting Started](#getting-started)
  - [Prerequisite](#prerequisite)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Status](#project-status)
- [Versioning](#versioning)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)

## Getting Started
[(Back to top)](#table-of-contents)
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisite
[(Back to top)](#table-of-contents)
To execute this project, you will need the following applications - 
* Pythnon 3 (or Anaconda distribution with Python 3)
* Jupyter or any other notebook

Anaconda distribution alone should be enough. Find it [here](https://www.anaconda.com/distribution/)

Following Python libraries
* os
* subprocess
* stat
* pandas_profiling
* numpy as np
* pandas as pd
* seaborn as sns
* matplotlib.pyplot as plt
* thinkstats2
* thinkplot
* datetime
* scipy
* sklearn

### Installation
[(Back to top)](#table-of-contents)
The project requires the following modules (both are included in the repository)
thinkplot.py, thinkstats2.py

The data file in the RawData folder is zipped for portability. It needs to be unzipped using WinRar or similar program.

## Usage
[(Back to top)](#table-of-contents)
This section will be updated as the project is developed.

## Project Status
[(Back to top)](#table-of-contents)
Completed

## Versioning
[(Back to top)](#table-of-contents)
Git is used for project versioning.

## Authors
[(Back to top)](#table-of-contents)
_Anirban Pal_

## Acknowledgements
[(Back to top)](#table-of-contents)
