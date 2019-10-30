# dsc-mod-5-project-ds-ft-071519

## Background

Gözalan Group, a Turkish company engaged in the supply of outdoor wear, is looking to run a 
marketing campaign with the objective of increasing their online sales. 

To ensure the greatest return on their marketing spend, they have asked their data science team to identify the customer segments with the greatest propensity to buy online.  They will use this information to efficiently allocate resouces to the segments with the greatest potential return.

## Data

To assist with this task Gözalan Group have provided a dataset relating to 12,330 online sessions that took place over a 1 year period.  Each record relates to a different user.  

The dataset consists of 10 numerical and 8 categorical attributes.  These attributes are:

- **Administrative**: The number of different administrative pages visited during the shopper's visit to the website
- **Administrative Duration**: The total time spent on administrative pages by the visitor during their session.
- **Informational**: The number of different informational pages visited during the shopper's visit to the website
- **Informational Duration**: The total time spent on informational pages by the visitor during their session.
- **Product**: The number of different product pages visited during the shopper's visit to the website
- **Product Duration**: The total time spent on product pages by the visitor during their session.
- **Bounce Rate**: Measured by Google Analytics.  A bounce is a single page session on a website.  Bounce rate is defined as the percentage of visitors who enter a website and then leave ("bounce") wihtout visiting any other pages.  
- **Exit Rate**: Measured by Google Analytics.  Calculated for a specific page as the proportion of times that page was the last page in the session before the customer left the site (as a percentage of all page views for that specific page).
- **Page Values**: Represents the average value for a web page that a user visited before completing an e-commerce transaction
- **Special Day**: Indicates whether the visit to the website falls on a special day such as Mother's Day, Valentine's Day etc.  
- **Month**: The month of the visit.
- **Operating System**: A numerical value indicating operating system type (non-ordinal). 
- **Browser**: A nummerical value indicating browser type (non-ordinal).
- **Region**: A numerical value indicating region (non-ordinal)
- **Traffic Type**: A numerical value indicating traffic type (non-ordinal)
- **Visitor Type**: Indicates whether this is a new or returning visitor.
- **Weekend**: Indicates whether or not it is the weekend.

In addition, there is a **Revenue** attribute, which indicates whether or not an online session culminated in an online purchase (True/False).  This will be used as the can be used as the classification (target) label.

## Approach

The complete approach to this task is detailed in the main Jupyter notebook, **project - predicting behavior of online shoppers.ipynb**.  

## Requirements

These instructions will guide you through the technical requirements that will need to be fulfilled, before running this project on your machine.

Before getting started, you will need to have Python installed on your machine. We recommend using Anaconda for this purpose, as it is delivered with more than 1,500 packages/libraries pre-installed.

## Libraries
To run these projects, you will first need to install the following libraries. If you have chosen to run Python through Anaconda, there is no need to individually install the below:

- **Pandas**: Used for data manipulation and analysis
- **Numpy**: Supports multi-dimensional matrices and arrays, provides a large number of mathematical functions
- **Matplotlib**: A 2D graphical plotting library
- **Seaborn**: Another data visualisation libary, based on Matplotlib
- **Sklearn**: Provides tools for data analysis
- **xgboost**: Enables use of the XG Boost weak learner algorithm
- **imblearn**: Provides methods to address issues relating to class imbalance
- **Itertools**: Implements a number of interator building blocks (e.g. permutations, combinations etc.)

## Forking & Cloning the Repository onto your Local Machine

1. Within Github, click 'Fork'
2. Once Forked, copy the link https://github.com/[YOUR NAME]/dsc-mod-5-project-online-ds-ft-071519
3. Open the command line and navigate to the folder you wish to save the projec to
4. Type 'git clone https://github.com/[YOUR NAME]/dsc-mod-5-project-online-ds-ft-071519'
5. Open a new command line window, type 'jupyter notebook'
6. A Jupyter notebook will open. Navitage to the folder in which your project is located, open the Jupyter notebook. You are ready to get started.


## Files
The relevant files within this repository are as follows:

- **README.md**: The file you're reading now.
- **project - predicting behavior of online shoppers.ipynb**: This is the Jupyter notebook which contains the indepth statistical analysis and models
- **online_shoppers_intention.csv**: This file contains the data used during the investigation
- **Presentation.pdf**: This is a set of slides which provides a non-technical overview of the project's findings

