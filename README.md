# TransportDemand
A quick prototype made in order to visually display data for bus journeys over time, this website was mostly a proof of concept. 
The data was downloaded and then manipulated locally using Apache Drill (using SQL commands). The original data was stored in a shape file, and the coordinates had to be transformed so that all datasets were using the same coordinate formats.


Please note that the data contained on the website has been changed, and does not actually represent actual data from TFL. These changes were made in order to allow this website to be shown publicly. 


If asked to scale this solution, I would not process the incoming data in Javascript, I would create a database and read the information from there. However, as previously mentioned, this website was built in a few hours to demonstrate a proof of concept, and thus certain methodologies were used that would not be implemented in a real project.


geotools2.js is required locally to allow the website to function properly. 
