# PowerTAC Weather XMl Generator

A rewrite of the weather server to offer a fast and efficient way to get a weather.xml file for a server.

## Install

`pip install -r requirements.txt`

## Use

```bash
python main.py #outputs a weather.xml file
```

The code takes inspiration from the [original weather server](https://github.com/powertac/powertac-weather-server)
but doesn't host the data. This could be added though, if needed.

## What it does
It downloads the weather files from knmi.nl and processes them into a xml file with a format compatible to the powertac-server
format