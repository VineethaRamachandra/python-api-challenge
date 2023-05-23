# python-api-challenge
Pandas-api-challenge is the main directory which contains the following project files/sub-directories:

- "WeatherPy" sub-directory contains following files:
		 - WeatherPy.ipynb (Jupiter notebook file which contains the actual code)
     - VacationPy.ipynb  (Jupiter notebook file which contains the actual code)
     - api_keys.py file which contains API Keys for OpenWeatherMap API and Geoapify API.
	
	"output_data" sub-directory contains following output csv and image files:
	
       - cities.csv  which extracts cities from OpenWeatherMap API.
       - Fig1.png (Scatter plot for City Max Latitude vs. Temperature).
       - Fig2.png (Scatter plot for City Max Latitude vs. Humidity).
       - Fig3.png (Scatter plot for City Max Latitude vs. Cloudiness).
       - Fig4.png (Scatter plot for City Max Latitude vs. Windspeed).
       
  ReadME.md - Current file which desribes Project structure, analysis of different regression plots.

From the liner regression plots in WeatherPy.ipynb, we can infer that that,

	1) The cities' "Latitudes and max temperatures" are negatively correlated for "northern hemisphere" as the r-value is around 0.64 and the line has a negative slope of -0.35

The cities' "Latitudes and max temperatures" are positively correlated for "southern hemisphere" as the r-value is around 0.64 and the line has a positive slope of 0.38

	2) 
The "cities' Latitudes and Humidity" are slightly negatively correlated for "northern hemisphere" as the r-value is around 0.01 and the line has a negative slope of 0.09

The cities' "Latitudes and Humidity" are slightly positively correlated for "southern hemisphere" as the r-value is around 0.01 and the line has a positive slope of 0.13

	3) The cities' "Latitudes and Cloudiness" are slightly positively correlated for "northern hemisphere" as the r-value is around 0.003 and the line has a positive slope of 0.11
  
	The cities' "Latitudes and Cloudiness" are negatively correlated for "southern hemisphere" as the r-value is around 0.001 and the line has a negative slope of 0.23
	
	4) The cities' "Latitudes and wind Speed" are slightly positively correlated for "northern hemisphere" as the r-value is around 0.01 and the line has a positive slope of 0.01
	
The cities' "Latitudes and wind Speed" are slightly negatively correlated for "southern hemisphere" as the r-value is around 0.05 and the line has a negative slope of 0.05!

Following external link was referred to resolve  ModuleNotFoundError: No module named 'citipy' ModuleNotFoundError
Link: https://www.roseindia.net/answers/viewqa/pythonquestions/58615-ModuleNotFoundError-No-module-named-citipy.html


