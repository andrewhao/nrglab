## nrglab

Python notebooks for home energy efficiency analysis

This is for exploratory analysis around home efficiency. It fuses hourly energy usage information from PG&E (electric/gas), as well as sensor data from the following third-party sources:

* PG&E daily/hourly billing reports (exported from pge.com)
* Nest home data report (data can be exported from [takeout.google.com](https://takeout.google.com)) that tracks furnace usage
* [InfluxDB](https://www.influxdata.com/) temperature data (I have multiple Raspberry Pi's recording ambient data)
* [Meteostat](https://dev.meteostat.net/) for hourly historical temperatature readings

Follow along in `[nrglab.ipynb](https://github.com/andrewhao/nrglab/blob/main/nrglab.ipynb)`
