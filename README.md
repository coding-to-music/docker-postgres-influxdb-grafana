# docker-postgres-influxdb-grafana

# 🚀 Multi-container docker app with Postgres, InfluxDB and Grafana. Building animated maps with GeoLoop Panel plugin. Using COVID-19 data 🚀

https://github.com/coding-to-music/docker-postgres-influxdb-grafana

From / By Aleksey Piskun https://github.com/viktorsapozhok

https://github.com/viktorsapozhok/docker-postgres-influxdb-grafana

https://viktorsapozhok.github.io/docker-postgres-grafana/

https://github.com/datasets/covid-19

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/docker-postgres-influxdb-grafana.git
git push -u origin main
```

# docker-postgres-influxdb-grafana

This tutorial provides a quick guide of how to install a dashboard environment
from Grafana, Postgres and InfluxDB with docker-compose, create map overlays with Worldmap Panel plugin and
build animated maps using GeoLoop Panel plugin.

To illustrate the process of building the animated maps with GeoLoop,
we will use time series data tracking the number of people affected by COVID-19 worldwide,
including confirmed cases of Coronavirus infection, the number of people died while
sick with Coronavirus, and the number of people recovered from it.

The data is borrowed from “covid-19” [dataset][1]
and stored as csv files in [data](https://github.com/viktorsapozhok/docker-postgres-influxdb-grafana/tree/master/data)
directory.

[Read the tutorial][2] for more.

<img src="https://raw.githubusercontent.com/viktorsapozhok/docker-postgres-influxdb-grafana/master/docs/source/images/dashboard.gif">

## License

MIT License (see [LICENSE](LICENSE)).

[1]: https://github.com/datasets/covid-19
[2]: https://viktorsapozhok.github.io/docker-postgres-grafana/ "Docker with postgres, influxdb and grafana"
