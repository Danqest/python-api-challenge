# python-api-challenge

This activity is an exercise in utilizing the Python "requests" library to make API calls to different web services which return a JSON that must be parsed for relevant data, which is then further summarized using charts and geographical plots.
The first Jupyter notebook (WeatherPy) requests several hundred datapoints relating to various cities and plots comparative statistical analysis for each city, such as latitude vs temperature, humidity, wind speed, and so on, followed by a statistical regression and correlation between each comparison.
The second Jupyter notebook (VacationPy) uses some of the output datapoints from the prior notebook and makes requests to find nearby hotels within certain parameters (i.e. within 10,000 meters) of each city, which is then plotted on an interactive geographical plot.
