# Twitter-and-Match-Performance-Data-Set
Associated data for the master thesis

This GitHub repository includes 4 data sets used for my master thesis. In total 124’341 Tweets from 31 selected ATP and WTA athletes are collected and linked with 8'095 respective match day performances. This repository includes 4 distinct data files.

The data file "Athletes Twitter Data" includes the Tweets from 31 ATP and WTA athletes including the original Tweet text.
In the "Athletes Match Data" data set, data and statistics of the 31 ATP/ WTA athletes from matches between 2012 and 2018 can be found. These two data sets are linked so that the number of tweets posted 36 hours prior to a match could be aggregated. This can be found in the data set "Twitter Usage Analysis". Finally the athletes' mood is detected by the application of a sentiment analysis using the Vader lexicon. The athletes' mood is inferred from the post content from Tweets posted 36 hours prior to a match. The data set "Athletes' Mood" contains the average polarity score before a given match. As both the post activity and the pre-match mood is related to the athletes' performance, the latter two data sets include the chosen performance variable - the first serve fault.

Acknowledgements
The full data set was complied with data from various open source repositories. Therefore deep gratitude is expressed towards Jeff Sackmann, who compiled ATP and WTA match data including match statistics. Furthermore, tennis-data.co.uk is acknowledged for providing ATP and WTA match data. Lastly, wettpoint.tennis.com is acknowledged for providing the start times of ATP and WTA matches.
