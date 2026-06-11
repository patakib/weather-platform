# Weather Platform
Data and API provided by: https://open-meteo.com/ - Thank you very much for making high quality weather data available.

## Objective
the main goal is to create a multi-platform automated setup for getting weather forecast data.

Several platforms are included:
- local (Linux - Arch- or Debian-based)
- cluster - coming soon...

## Architecture

Source repository: https://github.com/patakib/weather-app  
That repo contains all the logic for the actual application.

### Local Bootstrap

```configuration``` folder includes all necessary files for Ansible that are needed to bootstrap a (Linux) server with the Weather Python project.

```cd local```
```ansible-playbook -i inventory.yml bootstrap.yml -K```
Then it asks for sudo password (this is the -K option).

It should clone the app, create the necessary folders for data and install the Python environment in ```{YOUR_HOME_FOLDER}/weather-app```.


