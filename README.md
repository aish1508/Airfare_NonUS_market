# Airfare_NonUS_market
This project will draw upon QL2’s airfare  data to analyze longer term travel trends to help customers identify potential changes in pricing or offering strategies. The goal is to provide QL2’s customers with insightful analysis and trend:
1. Market Insights: Identify and describe pricing trends by market/carrier/agency and
identify markets/carriers/agencies that are unique/outliers compared to general trends.
2. Data Complexity: One struggle in analyzing travel pricing data is inconsistency in the
collection and availability of data.

Data Dictionary:
Airfare:
● COLLECT_DATE - The date that the price was collected from the web.
● CURRENCY - Current of collected price
● CXR - Airline IATA code -
(https://www.iata.org/en/publications/directories/code-search/)
● DDATE - Departure date of the flight
● DFLIGHT - Departure flight number
● DROUTE - Details of the airports
● DSTP - Number of stops on departing flight
● DTIME - Time of departure
● FARE - Price of flight
● FROM_AIRPORT - Departing airport in IATA code
● QL2_QTS - An indexed collection data to help with querying data.
● SITE - Website that pricing record was collected from
● TO_AIRPORT - Arriving airport of the flight.
