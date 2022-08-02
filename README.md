# Load test

## Stack
### [Grafana](https://grafana.com/grafana/) - Dashboard

### [InfluxDB](https://www.influxdata.com/products/influxdb-overview/) - Timeseries DB

### [K6](https://k6.io/) - Load testing tool

___
## Commands
```
docker-compose up -d grafana influxdb
docker-compose run k6 run /scripts/load-test.js
```