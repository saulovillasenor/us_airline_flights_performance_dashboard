# us_airline_flights_performance_dashboard

# Interactive Dashboard about US Domestic Airline Flights Performance
This is the final project of the course [Data Visualization with Python](https://www.coursera.org/learn/python-for-data-visualization), which is part of the [Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) offered by IBM in Coursera. The Data Visualization with Python course is the 8th out of 10 courses which complement the professional certificate. This project was created in another repository in order to deploy the application in a server and make it available for anyone. If you wish to view the full repository for the IBM Data Science Professinal Certificate, please follow this [link](https://github.com/saulovillasenor/ibm_data_science_professional_certificate). You will find the reading, code notebooks, notes, projects, quizes and all the material from the certificate.

## Story
As a data analyst, you have been given a task to monitor and report US domestic airline flights performance. Goal is to analyze the performance of the reporting airline to improve flight reliability thereby improving customer reliability. Below are the key report items:
	- Yearly airline performance report 
	- Yearly average flight delay statistics
NOTE: Year range is between 2005 and 2020.

## Components of the report items
1. __Yearly airline performance report__. For the chosen year provide:
	- Number of flights under different cancellation categories using bar chart.
	- Average flight time by reporting airline using line chart.
	- Percentage of diverted airport landings per reporting airline using pie chart.
	- Number of flights flying from each state using choropleth map.
	- Number of flights flying to each state from each reporting airline using treemap chart.
2. __Yearly average flight delay statistics__. For the chosen year provide:
	- Monthly average carrier delay by reporting airline for the given year.
	- Monthly average weather delay by reporting airline for the given year.
	- Monthly average natioanl air system delay by reporting airline for the given year.
	- Monthly average security delay by reporting airline for the given year.
	- Monthly average late aircraft delay by reporting airline for the given year.

3. Requirements to create the dashboard
	- Create dropdown using the reference here
	- Create two HTML divisions that can accomodate two components (in one division) side by side. One is HTML heading and the other one is dropdown.
	- Add graph components.
	- Callback function to compute data, create graph and return to the layout.

## Review
Search/Look for review to know how commands are used and computations are carried out. There are 7 review items.
- REVIEW1: Clear the layout and do not display exception till callback gets executed.
- REVIEW2: Dropdown creation.
- REVIEW3: Observe how we add an empty division and providing an id that will be updated during callback.
- REVIEW4: Holding output state till user enters all the form information. In this case, it will be chart type and year.
- REVIEW5: Number of flights flying from each state using choropleth
- REVIEW6: Return dcc.Graph component to the empty division
- REVIEW7: This covers chart type 2 and we have completed this exercise under Flight Delay Time Statistics Dashboard section
