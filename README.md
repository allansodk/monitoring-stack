# monitoring-stack

Det, der holder øje med homelabbet: Prometheus skraber node_exporter og cAdvisor,
Grafana viser det, Loki samler logs. Dashboards ligger i `grafana/dashboards`.

```bash
docker compose up -d   # Grafana på :3000
```
Mere på <https://allanso.dk/homelab>.
