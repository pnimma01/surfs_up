# surfs_up

**Note:**
I worked with Aman Gill for this challenge. We followed pair-programming methodology and the code and readme was co-created.


## **Overview of the analysis:**

We have been dreaming of a life selling ice cream and surfing supplies in the beautiful islands of Hawaii, specifically, the island of Oahu, and now is our chance! With the help of an investor named W. Avy, our dreams are becoming closer to reality every day. The only caveat? W. Avy wants some data analysis to be assured of his investment.

W. Avy wants us to analyze weather data acquired from various weather stations across Hawaii. He has supplied us with an SQLite database containing temperature and precipitation recordings from 9 different stations. Using SQLalchemy, we will make a connection to the SQLlite database and query the temperature and precipitation records using SQLalchemy. Finally, we will create a web page to present our findings to W. Avy's board of directors using flask.

## **Results**
W. Avy requested that we analyze the data and give him a summary of the temperature data for the months of June and December, covering years starting 2010 to 2017. We performed can fulfill the request by querying the sqlite data that was provided to us. The data sqlite data is imported into a pandas dataframe, from which following summary statistics were gathered.

Here is a summary of temperatures in June and December:

**June Temperature**

![June Temperature](https://github.com/pnimma01/surfs_up/blob/643e42344952062fb8f4930466601710a4501ef5/Challenge/Resources/June_Temperature.png)

**December Temperature**

![December Temperature](https://github.com/pnimma01/surfs_up/blob/643e42344952062fb8f4930466601710a4501ef5/Challenge/Resources/Dec_Temperature.png)

Here is a key difference between the 2 months.

1. There are roughly 200 less temperature readings in December than in June
    This finding should not impact our analysis, as each weather station is recording multiple times per day.
    The average temperature in December is ~ 5 degrees less than it is in June, which is a reasonable considering the seasons.

## **Summary**

Now that we have a good understanding of the average temperature in Oahu for most of the year, it's safe to say that Oahu is a prime location for an ice cream and surf shop. The weather year around is relatively stable, the December average temperature is a pleasant 71 degrees, warm enough for a scoop of ice cream, and some surfing. While it is an exciting outcome of our analysis, we don't want to leave any stones unturned and want to make sure that we also look at percipitation data for both the months. 

Using the sqlite data that was provided, and loading the data into a pandas dataframe, we come up with following summaries for percipitation.

**June Percipitation**

![June Temperature](https://github.com/pnimma01/surfs_up/blob/643e42344952062fb8f4930466601710a4501ef5/Challenge/Resources/June_Percipitation.png)

**December Percipitation**

![December Temperature](https://github.com/pnimma01/surfs_up/blob/643e42344952062fb8f4930466601710a4501ef5/Challenge/Resources/December_Percipitaion.png)


Looking at the summaries, 