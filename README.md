# eventful_evert_search 
This code is based on Python 3.5 and I Use eventful API to search event and save it to csv file

This function handles event search and outputs the all result responsed by eventful api into csv file, which is named events.csv in the same directory as event_search.py


The fast way to run this event_search.py is using command prompt.

In command prompt, run the following command propmt

> python event_search.py location start_date end_date

location: a string that determines the event location, such as New-York, each word is separated by hyphen.

start_date: a string that determines the range you want to search, such as 20160101, which stands for Jan 01, 2016
end_date: a string that determines the range you want to search , such as 20160131, which stands for  Jan 31, 2016

for example, I'd like to search all events in New York City throwing in January 2016.

In command promt, type in the following command.

> python event_search.py New-York 20160101 20160131

You will get event.csv listing all events throiwng in January 2016.




NOTICE:
Because of api limitation, it can search the 250 events a day because of api limitation.

I only choose the most popular events.

The default event features I choose is 

latitude	longitude	start_time	stop_time	all_day	city_name	region_name	postal_code

You can design the event features you need (based on variable event_features in main()) to export.

    
Thank you.

