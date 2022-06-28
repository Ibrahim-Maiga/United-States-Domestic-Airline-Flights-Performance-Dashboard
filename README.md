# United-States-Domestic-Airline-Flights-Performance

In this Code Pattern, we will implement a live dashboard for US Domestic Airline Flights Performance using Folium and Plotly.

Goal is to monitor and report the performance of the airlines declaring their flights to improve flight reliability thereby improving customer reliability. 

Below are the key report items,  
-Yearly airline performance report  
-Yearly average flight delay statistics 

NOTE: Year range is between 2005 and 2021. 

Components of the report items:

*Yearly airline performance report 

For the chosen year provide,  
-Number of flights under different cancellation categories using bar chart. 
-Average flight time by reporting airline using line chart. 
-Percentage of diverted airport landings per reporting airline using pie chart. 
-Number of flights flying from each state using choropleth map. 
-Number of flights flying to each state from each reporting airline using treemap chart. 

*Yearly average flight delay statistics  

For the chosen year provide,  
-Monthly average carrier delay by reporting airline for the given year. 
-Monthly average weather delay by reporting airline for the given year. 
-Monthly average national air system delay by reporting airline for the given year. 
-Monthly average security delay by reporting airline for the given year. 
-Monthly average late aircraft delay by reporting airline for the given year.


Expected Layout

Two dropdown menus: For choosing report type and year
Each dropdown will be designed as follows:
-An outer division with two inner divisions (as shown in the expected layout)
-One of the inner divisions will have information about the dropdown and the other one is dropdown.
Layout for adding graphs.
Callback function to compute data, create graph and return to the layout.

