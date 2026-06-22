# Monitoring Stack 📊

Full observability: metrics, logs, traces with Prometheus + Grafana + Loki + Tempo.

## Components

| Component | Purpose | Retention |
|-----------|---------|-----------|
| Prometheus | Metrics | 30 days |
| Grafana | Dashboards | N/A |
| Loki | Logs | 14 days |
| Tempo | Traces | 7 days |
| Alertmanager | Alerts | N/A |

## Deploy

```bash
helm upgrade --install monitoring . -f values-production.yaml
```

## License

Apache 2.0