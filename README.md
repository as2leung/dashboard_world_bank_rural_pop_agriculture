# dashboard_world_bank_rural_pop_agriculture
A dashboard visualization rural population and agriculture data from the World Bank. Created with Flask, Plotly and Bootstrap library.

The dashboard is hosted on Heroku and a first load may take some time as the dyno needs to awake from sleep. View the dashboard here: 
[World Bank - Rural Population and Agriculture](https://asleung-dsb1-world-bank-rural.herokuapp.com/)

## Table of Contents
* [Project Motivation](#motivation)
* [List of key files and folders](#files)
* [Libraries](#libraries)
* [Licensing, Authors, Acknowledgements](#creators)


## Project Motivation<a name="motivation"></a>

For this project, I created a dashboard to visualize World Bank Data on rural population and agriculture for the top 10 economies in the world. The backend uses Flask and Plotly in order to visualize the data with interactive plots with Python used to script the data cleaning and wrangling. The HTML front uses the Bootstrap library. 


## List of key files and folders<a name="files"></a>

* worldbank.py - py script to run the package
* data  - folder containing csv files from the World Bank
* worldbankapp - contains the app's front-end and back-end scripts (including the html scripts and passing the plots to the front-end)
* wrangling_scripts - contains the data wranging functions and scripts for the plots that are passed to the front-end


## Libraries

* Pandas
* Plotly
* Flask
* Bootstrap
* JSON

## Additional Information

* Heroku - used to host app
* Git - version control used to manage app changes and upload

## Licensing, Authors, Acknowledgements<a name="creators"></a>

The data can be retrived from the [World Bank](https://data.worldbank.org/) 

* Andrew Leung
    - [https://github.com/as2leung](https://github.com/as2leung)

