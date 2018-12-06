# DSCI511 Project
## 60 Days of Weather Data
Column information for WeatherData.csv dataset extracted from WeatherUnderground.com website:
******************************************************************************************************************************************
Provided by:
Kiana Montazeri
Dec 4th, 2018
Drexel University, Philadelphia, PA
*****************************************************************************************************************************************
 Columns | Definition |
 --- | --- |
 avgoktas 							                   |Average Okta Number
 coolingdegreedays: 					           |Cooling Degree Days
 coolingdegreedaysnormal: 		        |Normal Cooling Degree Days
 dewpoint: 					               	   	|Dew Point
 fog: 							                	      |Fog
 gdegreedays: 					                	|Growing Degree Days
 hail: 								                     |Hail
 heatingdegreedays: 					           |Heating Degree Days
 heatingdegreedaysnormal: 			       |Normal Heating Degree Days
 humidity: 							                  |Humidity
 icon:							                      	|Type of Weather(sunny, cloudy, …)
 max_dewpoint:					                	|Maximum Dew Point
 max_humidity:					                	|Maximun Humidity
 max_pressure:					            	    |Maximum Pressure
 max_temperature:						             |Maximum Temperature
 max_temperature_normal:				        |Normal Maximum Temperature
 max_temperature_record:				        |Record Maximum Temperature
 max_temperature_record_year:		    	|Year of Record Maximum Temperature
 max_visibility:					          	    |Maximum Visibility
 max_wind_speed:				          	    	|Maximum Wind Speed
 min_dewpoint:					                	|Minimum Dew Point
 min_humidity:					            	    |Minimum Humidity
 min_pressure:					                 |Minimum Pressure
 min_temperature:					             	|Minimum Temperature
 min_temperature_normal:				        |Normal Minimum Temperature
 min_temperature_record:				        |Record Minimum Temperature
 min_temperature_record_year:		    	|Year of Record Minimum Temperature
 min_visibility:					               |Minimum Visibility
 min_wind_speed:						              |Minimum Wind Speed
 monthtodatecoolingdegreedays:		    |Month to Date Cooling Degree Days	
 monthtodatecoolingdegreedaysnormal:|Normal Month to Date Cooling Degree Days
 monthtodateheatingdegreedays:		    |Month to Date Heating Degree Days	
 monthtodateheatingdegreedaysnormal:|Normal Month to Date Heating Degree Days
 monthtodateprecipitation:			       |Month to Date Precipitation
 monthtodateprecipitationnormal:  		|Normal Month to Date Precipitation
 monthtodatesnowfall:				          	|Month to Date Snowfall
 precip:								                    |Precipitation
 precipnormal:						                |Normal Precipitation
 preciprecord:					                	|Record Precipitation
 preciprecordyear:				             	|Year of Record Precipitation
 precipsource:						                |Precipitation Source
 pressure:							                   |Pressure
 rain:								                      |Rain
 since1jancoolingdegreedays:			|Since Jan 1st Cooling Degree Days
 since1jancoolingdegreedaysnormal:		|Normal Since Jan 1st Cooling Degree Days
 since1janprecipitation:				|Since Jan 1st Precipitation
 since1janprecipitationnormal:		|Normal Since Jan 1st Precipitation
 since1julheatingdegreedays:			|Since July 1st Heating Degree Days
 since1julheatingdegreedaysnormal:		|Normal Since July 1st Heating Degree Days
 since1julsnowfall:					|Since July 1st Snowfall
 since1sepcoolingdegreedays:			|Since Sep 1st Cooling Degree Days
 since1sepcoolingdegreedaysnormal:		|Normal Since Sep 1st Cooling Degree Days
 since1sepheatingdegreedays:			|Since Sep 1st Heating Degree Days
 since1sepheatingdegreedaysnormal:		|Normal Since Sep 1st Heating Degree Days
 snow:								|Snow
 snowdepth:							|Snow Depth
 snowfall:							|Snowfall
 temperature:						|Temperature
 temperature_normal:					|Normal Temperature
 thunder:							|Thunder
 tornado:							|Tornado
 visibility:							|Visibility
 wind_dir:							|Wind Direction
 wind_dir_degrees:					|Wind Direction Degrees
 wind_speed:							|Wind Speed
 Date:								|Date
 AirportCodes:						|Airport Abbreviation
 AirportNames:						|Airport Name
******************************************************************************************************************************************
Airport Codes:
 - 'JAX', 'GJT', 'TRI', 'IAH', 'EYW', 'DAL', 'AZO', 'AVL', 'INT', 'BGR', 'AUS', 'DAY', 'ABE', 'HPN', 'OMA', 'ATL', 'FAT', 
 - 'RIC', 'GRR', 'SMF', 'BOI', 'DET', 'MIA', 'MCO', 'CHS', 'SBN', 'SFO', 'LAS', 'AMA', 'PSP', 'FSD', 'JFK', 'DCA', 'HIO', 
 - 'DTW', 'BDL', 'HVN', 'DLH', 'FAY', 'ABQ', 'SNA', 'ROC', 'AUG', 'MHT', 'ORF', 'CVG', 'EWR', 'FAR', 'STL', 'SAV', 'TTN', 
 - 'CLT', 'MDW', 'SWF', 'MCI', 'RDU', 'ONT', 'BWI', 'EUG', 'GPT', 'PDX', 'BTV', 'LAX', 'DHN', 'ALM', 'TYS', 'LGA', 'LEX', 
 - 'PUB', 'HYA', 'CPR', 'SAN', 'MSY', 'COS', 'CAE', 'YUM', 'PVD', 'RNO', 'HSV', 'PSC', 'CHA', 'RSW', 'PIE', 'GSP', 'ALB', 
 - 'RAP', 'TOL', 'ACK', 'SAT', 'SDF', 'CID', 'EVV', 'LIT', 'RST', 'ORD', 'ELP', 'LGB', 'FYV', 'TPA', 'MKE', 'PHL', 'TUS', 
 - 'BUR', 'ORH', 'AGS', 'PWM', 'FLL', 'SYR', 'BIL', 'CMH', 'FNT', 'DFW', 'ICT', 'LAN', 'IND', 'RUT', 'RKS', 'HTS', 'PHX', 
 - 'OAK', 'CAK', 'BUF', 'DSM', 'MSN', 'LNK', 'SEA', 'ISP', 'MAF', 'FWA', 'GRB', 'AVP', 'PFN', 'CRP', 'BTL', 'MDT', 'PIR', 
 - 'SLE', 'BNA', 'SGF', 'CYS', 'CKB', 'MPV', 'BTR', 'SJC', 'MYR', 'GSO', 'MOB', 'TUL', 'JAC', 'BIS', 'CRW', 'ASE', 'PHF', 
 - 'CLE', 'SHV', 'MSP', 'DAB', 'PIA', 'FLG', 'SRQ', 'PBI', 'ACY', 'MGM', 'GEG', 'PIT', 'SLC', 'ROA', 'PNS', 'BOS', 'MBS', 
 - 'BHM', 'MEM', 'DEN', 'MLI', 'HOU', 'XNA', 'JAN', 'ERI', 'LBB', 'OKC']
******************************************************************************************************************************************
