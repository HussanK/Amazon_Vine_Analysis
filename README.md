# Amazon_Vine_Analysis

## Overview

In this challenge we took Amazon reviews, put them through the ETL process (Extract, transform, load) into an AWS database we created and then further took that data and analyzed
it. I chose to analyze the digital video game market. It is something widely available and currently starting to command the whole video game market as opposed to physical copies. 
We used AWS, postgressql, PySpark, and Pgadmin for the first deliverable as well as Google Collab, and in the second on I chose again to use PySpark and Google Collab. 

## Results
The most interesting thing in the digital video games market is this.

There are 0 paid reviews for this market.  Or at the very least none that have been rated more then 50% helpful. 
This clearly skewed the results towards the unpaid results as those became the entirety of our data. 
The main thing left to report was that as shown below roughly 38 percent of all reviews were 5-star reviews. 

### Summary
These numbers simply show that the Digital Video Game market is not somewhere that Vine would thrive as there are no paid reviews for these games. Looking across all the data 
regardless of how helpful it is viewed as or not may produce better data for this test but overall, I would be looking into other markets as this one is not being used with Vine
