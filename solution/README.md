
# Logs scraping and monitoring solution for microservices in Kubernetes

## Log management
- **ELK stack**: Filebeat, Elasticsearch, Logstash, Kibana
    -- Reads log data from Kubernetes log files.
- [**Elasticalert 2**](https://github.com/jertel/elastalert2): For setting up rules for alerting on anomalies based on data pulled from Elasticsearch. 
## Monitoring
- **Prometheus**: Monitores and exports metrics and insights in real time from a Kubernetes cluster as well as custom defined endpoint like microservices.
- **Grafana**: For visualizing time series data pulled from Prometheus
- **Zipkin**: Distributed tracing system for correlating between the requests sent and received by the microservices

## 🔗 Helm charts used
- [ElastAlert 2](https://artifacthub.io/packages/helm/elastalert2/elastalert2)
- [Elasticsearch](https://artifacthub.io/packages/helm/bitnami/elasticsearch)
- [Logstash](https://artifacthub.io/packages/helm/bitnami/logstash)
- [Kibana](https://artifacthub.io/packages/helm/bitnami/kibana)
- [Filebeat](https://artifacthub.io/packages/helm/elastic/filebeat)
- [Prometheus](https://artifacthub.io/packages/helm/bitnami/kube-prometheus)
- [Grafana](https://artifacthub.io/packages/helm/bitnami/grafana)

