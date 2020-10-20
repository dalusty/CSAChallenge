# Weather Data Challenge

## Introduction

This challenge was submitted by Dave Lusty.

Often when working with analytics we talk about merging in weather data to enable us to analyse sales against weather. In order to do this we must first source and import that weather data! The purpose of this challenge is to find a suitable weather service which can deliver either actual weather or predicted weather, and use some automated method to retrieve that data on an ongoing basis. The data needs to end up in a usable format such as CSV, TSV, JSON, XML, Parquet or something else. Incoming data might be in JSON from an API, XML or CSV from a file service, or GRIB from a weather specialist, or some other format.

## Instructions

Using any available Azure technology you need to collect weather data for London, Reading and Manchester in the UK as well as Paris, France and Seattle, USA.
The output should be a storage account or database containing structured data about the weather either past, present, or future for these locations arranged by date.

![getWeatherData.png](images/getWeatherData.png)

To do this you must fulfil the following:
 - Find a weather service
 - Connect to the weather service
 - Set up a schedule of some kind
 - Collect data for the above locations
 - Transform the format
 - Store the data