# query-exporter-helm
A helm chart for query-exporter, used to export Prometheus metrics from SQL queries

## Installing the Chart

To install the chart with the release name `query-exporter-helm`:

```console
helm repo add tablecheck-query-exporter-helm https://tablecheck.github.io/query-exporter-helm/
helm upgrade --install query-exporter-helm tablecheck-query-exporter-helm/query-exporter-helm
```