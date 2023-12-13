Restful Booker API - Update Booking

Overview
This repository provides scripts to automate testing for the "Update Booking" endpoint in the Restful Booker API. These scripts cover various scenarios to ensure comprehensive testing.
API Endpoint

    Method: PUT
    Endpoint: https://restful-booker.herokuapp.com/booking/:id
    Example: https://restful-booker.herokuapp.com/booking/1

Test Scenarios
The scripts focus on updating booking information, including scenarios with both valid and invalid data conditions.
Test Data

The payload used for testing includes:

json

{
  "firstname": "James",
  "lastname": "Brown",
  "totalprice": 111,
  "depositpaid": true,
  "bookingdates": {
    "checkin": "2018-01-01",
    "checkout": "2019-01-01"
  },
  "additionalneeds": "Breakfast"
}

Prerequisites

Before running the scripts, ensure you have the requests library installed:

bash

pip install requests

Usage

    Clone this repository to your local machine.
    Open a terminal and navigate to the repository folder.

bash

cd path/to/repository

    Run the Python script to execute the test scenarios:

bash

python update_booking_test.py

