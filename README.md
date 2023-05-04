
# prom-grafana-dockercompose

A docker compose file to run Prometheus, Grafana and exporters locally.

Step 0:
Clone this repo

Step 1:
Put the `prometheus.yml` file in `/etc/prometheus` folder

Step 2:
`cd` to the `prom-grafana-dockercompose` folder and use the command `docker compose up` to run the containers

Step 3:
Go to [localhost:9090](https://localhost:9090) and check if Prometheus is scraping the targets correctly

Step 4:
Go to [localhost:3030](https://localhost:3030) and login into Grafana

`user: admin`
`pw: secret`

Step 5:
Add Prometheus as Grafana's datasource using [http://host.docker.internal:9090](http://host.docker.internal:9090) as the URL.


