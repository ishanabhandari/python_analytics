### Background on the Uber Trips Analysis Project
This is the canonical first data science project for lots of people - it's like a 'hello world' program!

I chose this project because it is a gentle introduction to data science in Python and there are many solutions available on Kaggle and on GitHub to learn the various ways to analyze this dataset.

Uber is a ride-sharing service that offers its services to most of the major cities in the USA and several countries around the world. 

The service matches a customer who needs a ride to a driver willing to provide the ride.The user requests the ride through the Uber app which then uses the customer's mapping coordinates to find the nearest ride.

### About the data used in this project

The data is for all the Uber rides in the month of September 2014 in New York City and its boroughs.

Under the data folder there is 1 datafile -
1. uber-raw-data-sep14.csv

The file has the following columns:

*Date/Time* is the date and time of the ride pickup

*Lat* is the latitude of the pickup

*Lon* is the longitude of the pickup

*Base* is the base company code from the TLC (NYC Taxi and Limousine Commission)

### How to install and run the project

1. Make sure Python 3 is installed and works fine on your machine.
2. Create a Python virtual env
   `python -mvenv venv`
3. Activate the virtual env
    `.\venv\Scripts\activate` ---> This an example for the Windows Operating System
4. Use pip to install the requirements.txt file
   `pip install -r requirements.txt`
5. Run the commands in the Jupyter notebook - *uber_trips_analysis.ipynb*

