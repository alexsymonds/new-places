# new-places

This repository contains my final project for CSCA 5632: Unsupervised Algorithms in Machine Learning at the University of Colorado, Boulder.

The United States is vast, and most people will never visit wide swaths of it. How can we be sure we’ve considered all the possible places that might be good fits for us to live, if a user doesn't even know about all the quaint towns in Montana that could be similar to his quaint town in Massachusetts? Or the mid-sized cities in the Midwest that would be a better fit for a heat-hater than the mid-sized city in the Deep South she currently inhabits?

I love to click around on Zillow or Redfin and imagine living in a totally different part of my country, but sometimes it can be hard to know where to start. I'd like a recommendation engine to be able to show me similar places I might not have thought of off the top of my head.

One possible solution, using unsupervised learning methods, is to cluster counties in the U.S. that have similar * vibes * , even if they're not geographically close to each other.

My goal was to allow a user to input a budget and see either a sorted list of best-match areas or some random recommendations.

I used the following data sources:

Quality of life: compiled by Zac Vaughan, combines data from various U.S. government agencies (the Census, EPA, USDA, Department of Education, etc.) as well as other good-quality data sources (UCSB's election results database, the Trust for Public Land, the Economic Policy Institute, etc.) to compile various information about U.S. counties. Accessed via Kaggle: https://www.kaggle.com/datasets/zacvaughan/cityzipcountyfips-quality-of-life/data

Housing prices: Median home prices and mortgage payment values compiled by the National Association of Realtors, https://public.tableau.com/app/profile/national.association.of.realtors/viz/Medianhomepricesbycounty-Q12024/Payment-County-Q12024

Vote totals in 2020: MIT Election Data and Science Lab, 2018, "County Presidential Election Returns 2000-2020", https://doi.org/10.7910/DVN/VOQCHQ, Harvard Dataverse, V13, UNF:6:GILlTHRWH0LbH2TItBsb2w== [fileUNF].
