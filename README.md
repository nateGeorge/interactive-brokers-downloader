This is a program I wrote to download interactive brokers stock data.  It automatically deals with connection issues and some errors,  
and saves the data to a database file (and .csv file if you wish). It can also compress the database file, since they can get large  
for shorter tick lengths.  If the data is not up to the latest date (i.e. you downloaded data before and want to add this weeks 
latest data), it will automatically take care of that.

The program is bundled into a nifty gui, with room for expansion of options, etc.  For a demo, see the video on youtube:  
https://www.youtube.com/watch?v=XoIkRVirTn8  
For now, it is limited to downloading one stock ticker and tick length at a time.