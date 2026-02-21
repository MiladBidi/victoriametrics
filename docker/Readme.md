
In this scenario, we are going to set up a very simple Victoria Metrics.

Prometheus = scrape + storage + query engine

vmagent  →  scrape
VictoriaMetrics  →  store + query

```
rate(node_cpu_seconds_total[1m])
```
