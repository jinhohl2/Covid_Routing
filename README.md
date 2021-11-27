### Covid Routing ###
by: Jin Ho Lee
* <jinhohl2@illinois.edu>

Project director: Richard Sowers
* <r-sowers@illinois.edu>
* <https://publish.illinois.edu/r-sowers/>

Copyright 2019 University of Illinois Board of Trustees. All Rights Reserved. Licensed under the MIT license

### Explanation of repository:
Analyze geographical and demographical data of Chicago urban area from Census. Find the best travel route of Covid-19 testing van to maximize the epimemilogical affect.

### File structure:  help the user out
* covid_routing.ipynb
	* Match geographic and demographic data of locations.
	* Find driving distance among locations. 
* CMAP data.ipynb
	* collects data from CMAP comprehecsive travel survey result for northern Illinois


* **data**: where the raw(ish) data is stored
	* Chicago travel survey:
		* https://www.cmap.illinois.gov/data/transportation/travel-survey
	* ZipCode_LatLng.csv  
		* Match the zip Code of the location to its geographic data (Latitude and Longitude)
		* From Chicago Data Guy: http://robparal.blogspot.com/2013/07/chicago-community-area-and-zip-code.html 	
	* ZipCode_Population.csv  
		* Match the zip code of the location to the population.
		* From Chicago Data Portal: https://data.cityofchicago.org/Health-Human-Services/Chicago-Population-Counts/		85cm-7uqa
	* all_140_in_17.P1.csv
		* Dataset regarding the population of census blocks in Chicago
		* from census.ire.org: http://census.ire.org/data/bulkdata.html
	* all_140_in_17.P8.csv
		* Dataset regarding the population of each race of census blocks in Chicago
		* from census.ire.org: http://census.ire.org/data/bulkdata.html
	* all_140_in_17.P9.csv
		* Dataset regarding the Hispanic population of census blocks in Chicago
		* from census.ire.org: http://census.ire.org/data/bulkdata.html
	* COVID-19_Cases__Tests__and_Deaths_by_ZIP_Code.csv
		* COVID-19 Cases, Tests, and Deaths in Chicago by ZIP Code
		* from healthdata.gov :https://healthdata.gov/dataset/covid-19-cases-tests-and-deaths-zip-code
timezone-aware datetimes.  
	* CMAP Data.zip: from https://datahub.cmap.illinois.gov/dataset/mydailytravel-2018-2019-public
		* data_dictionary.csv: Provides information of tables and variables
		* location.csv: Geographic location reported at any level of the household. 
		* person.csv: Data regarding each individual household member.
		* place.csv:  Place or destination that was reported individually by a household person for the household's instructed travel date
		* gps_place: Place that was reported by the GPS-based MyDailyTravel phone application during participant's travel reporting period.

The manuscript for this work is at <https://www.overleaf.com/project/5fb585e049231a413bc9a3bb>
___




Other resources at
* <https://www.makeareadme.com/>
* <https://help.github.com/articles/about-project-boards/>
