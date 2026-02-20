# Weather Platform
Data and API provided by: https://open-meteo.com/ - Thank you very much for making high quality weather data available.

## Objective
the main goal is to create a multi-platform automated setup for getting weather forecast data.

Several platforms are included:
- local (Linux - Arch- or Debian-based)
- cluster - coming soon...

## Architecture

This project involves several important parts of a data workflow, such as:
- getting data from API (in this case Weather Forecast API)
- storing data in data lake (locally in parquet files)
- transforming data as part of an ETL workflow
- ingesting data into data warehouse
- visualize data on dashboard

### Local Bootstrap

```configuration``` folder includes all necessary files for Ansible that are needed to bootstrap a (Linux) server with the Weather Python project.
```
```
```
```
