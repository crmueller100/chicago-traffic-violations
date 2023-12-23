# Overview
The goal of this project is to analyze where traffic violations are occurring in Chicago and how they have trended over time.

# Technical Stuff
The required dependencies are in `requirements.txt` and were managed using pip. Run the following commands in the terminal to download the necessary libraries:
```
$ python -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

Data was read utilizing the [Socrata API](https://dev.socrata.com/).


# References
All data was gathered from https://data.cityofchicago.org/.

[1] [Geospatial data](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6)

[2] [Red light camera violations](https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37/about_data)

[3] [Speed camera violations](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/about_data)