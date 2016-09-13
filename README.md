# eventful_evert_search
Use eventful API to search event and save it to csv file
Description:
   	This function handles event search. It performs the requested search, returning the results as an json file. 
   	Write the all returned result into csv file.
    
    Variable Definition:
  	event_key: a str that indicates Application key as provided by Eventful. Apply for key at http://api.eventful.com/keys
  	event_location: a location to use in filtering the search result. eg. "New York"
  	start_date: a str that determines the start date for searching, format: "yyyymmdd"
	end_date: a str that determines the end date for searching, format: "yyyymmdd"
    event_format: a list contains all Output Parameters
    event_fname: output csv file name


    Return: None
