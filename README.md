# SentinelScripts
Downloading data from copernicus Odata platform

This repository contains two scripts to allow users to download raw setinel-1 and sentinel-2 imagery from copernicus OData

Make sure you have created an Odata account on https://identity.dataspace.copernicus.eu/auth/realms/CDSE/login-actions/registration?client_id=cdse-public&tab_id=qDvE2bacKK4

Clone the repository and navigate toward the folder before opening the code 
Make sure to download the libraries present in the pycopern.yml file and make sure the utils.py file is present 

The code is fully automated. The only configuration needed is the Credential files that contain the inputs

Credential files formatting;

Make sure there is no spacing between any letters or between the '=' before inputting your requirements

COPERNICUS_USERNAME='insert_path_to_username'
COPERNICUS_PASSWORD='insert_path_to_password'
AOIPATH='insert_path_to_AOI'
STARTDATE=2024-01-01
ENDDATE=2025-02-01
CLOUDFILTER=20.00
OUTPUTNAME=IMAGEOUTPUT
