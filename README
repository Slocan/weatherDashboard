# Local Weather Dashboard

Code repository for custom weather dashboard in Grafana, using data from a Ecowitt GW1000 gateway

![Local Weather Dashboard](/Screenshot-Grafana.png?raw=true "Grafana Screenshot")

## Pre-requisites

Requirements:
- Telegraf
- Grafana
- Influxdb

Recommended:
- Apache or Nginx, acting as proxy to provide authentication and TLS encryption

## Installation

- Copy the .conf files from the telegraf folder to:
/etc/telegraf/telegraf.d/
After restarting telegraf, it will listen on port 7080 to receive the data from the gateway. Review your network to allow traffic to this port from the gateway.

- In grafana, Import the json from the grafana folder as a new dashboard

- In the Ecowitt WS app, set the Customzied upload to:
Protocol: Ecowitt
Server IP/Hostname: <Your telegraf installation hostname>
Path: /telegraf
Port: 7080
Upload interval: 30

## License
[MIT](https://choosealicense.com/licenses/mit/)
