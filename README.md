# kubernetes-logging-efk

This repository provides a Kubernetes-based logging solution using the Elasticsearch, Fluentd, and Kibana (EFK) stack.

## Scope

The repository contains configuration files for setting up Elasticsearch, Fluentd, and Kibana in a Kubernetes environment.

### Elasticsearch Configuration

- `elasticsearch/bitnamielastic-values.yaml`: Contains configuration settings for Elasticsearch, including security parameters, master node settings, and resource allocation.

### Fluent Bit Configuration

- `fluentbit/fluentbit-values.yaml`: Contains configuration settings for Fluent Bit, including service, input, filter, and output configurations.

### Fluentd Configuration

- `fluentd/bitnamifluentd-configmap.yaml`: Contains a ConfigMap for Fluentd, defining input and output configurations for log forwarding and processing.
- `fluentd/bitnamifluentd-values.yaml`: Contains configuration settings for Fluentd, including forwarder and aggregator parameters, environment variables, and resource allocation.

### Kibana Configuration

- `kibana/bitnamikibana-values.yaml`: Contains configuration settings for Kibana, including resource allocation, TLS configuration, and Elasticsearch connection parameters.
