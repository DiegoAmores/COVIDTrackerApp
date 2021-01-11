## INST 326 Final Project: COVID-19 Tracker <br>

Team Members: Kristen Wagner, Chandra Tamang, Minsung Kim, Diego Amores

## Introduction:

Our team has built a COVID-19 Tracker command-line interface to make users' lives a little easier during this global pandemic. Our interface allows users to get the latest COVID-19 information in various ways. It has many different functions built for our users. By using our interactive command-line, users can get the number of deaths for each state, the number of total cases by specific dates, the number of cases reported, see COVID-19 data visually, and so on.

## How to Run our Code Using Visual Code:

All the following scripts must be in the same directory:
- covid_tracker_app.py
- covid_information.py
- live_covid_information.py
- Delete Update_Report.csv

Install the following modules with the following commands:
For Windows, use python or else for Mac, use python3
- python -m pip install -U click
- python -m pip install -U matplotlib
- python -m pip install -U pandas
- python -m pip install -U pytest

Run the command-line with the following command:
python or python3 covid_tracker_app.py

If you are using a Mac, uncomment the following from covid_tracker_app.py:
- import ssl
- ssl._create_default_https_context = ssl._create_unverified_context

