# Final project essay

1. Now that you have seen many full research projects saved online as GitHub repositories do you plan to use GitHub for your future projects as a way to store code and data in the cloud and to share your progress with others?

Yes. I think GitHub is particularly useful for collaborating with others. Great way to work remotely with group members. 

2. Did you project accomplish the goals that you set out for yourself in your proposal? If not, why? What was the hardest problem in your project that you were able to overcome? What, if any, was a problem that you were unable to overcome in your project within the given time?

I accomplished the larger goal of making federal sentencing information much more accessible and interactive in a searchable, customizable way, but with several differences from my original proposal. My charts use DASH and are easy to use, visually clear and attractive, and offer a range of variables to choose from. So in all that the project was successful. 

The differences from my original plan: 

1) The enormous size of the data even for just one year was causing my computer heart attacks, so I narrowed the scope of my project to just the Southern District of NY. I chose the SDNY because it is the most influential and high profile of all the federal court districts, has an interesting history, and is  currently in the news because of the Michael Cohen case.  

2) I didn't develop a way to convert SPSS files to csv using python: it was unnecessary, and also wouldn't have worked in this case, because the original USSC data was split into two files (variables vs data) that needed to be joined in spss to form an .sav file. 

3) While I did make interactive, customizable charts, I decided not to make interactive tables because it seemed much less compelling than the interactive charts. (I did make a table in DASH which I did not include or develop beyond the basics.)

4) I ran out of time to do a map based visualization, though that I would like to pursure in the future. 

I also later sketched out two additional ideass I did not have time to make: 1) a heat map by district and 2) an animated data visualization tied to a scroll function in a website (to be coded in javascript). I also did not run regressions since I ended up working with a much smaller dataset. 

The hardest problem I was able to overcome was dealing with the massive data and its original SPSS oriented format: I eventually found another data source already in csv format (for a few years of data at least) and was able to combine datasets etc to make that work for one year (I became more familiar with pandas along the way). In general, if the dataset is small enough, I found it is easy enough to translate sav into csv format. And the other big challenge I overcame was just learning how to use DASH and make it work with my dataset.

Problem I was not yet able to overcome: I was not able to subset all the annual data in the .sav files (which I generated by using someone's computer that had SPSS on it) because they are way too big. So I only was able to work with one year's worth of data for now, which is a huge limitation in terms of analysis.   


3. Do you feel that you've learned the skills necessary to perform data analysis in Python, and to write your own program or pipeline for data analysis? What skills do you think you need to work on further, and where would you look to find more information about learning these skills?

I became comfortable with pandas and numpy, and got to know how to use DASH as well, so that was all great and useful. I need to get better at data wrangling, which I may (likely) do by taking a data structures course in the fall, and also be going over the Python & Data Analysis book. I also plan to do more exercises in another Python book that I really like and which is fun to use because of its creative examples and very clear explanations. I think that will improve the speed and quality of my coding. Also, though I know how to set up a model and run a multivariate regression, etc I want to improve my data analysis skills this summer by reading a stats book that I got and doing some exercises in R, etc. 


