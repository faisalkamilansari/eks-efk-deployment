# EFK Stack Deployment on Manual Kubernetes Cluster

This repository contains the configuration for deploying an EFK (Elasticsearch, Fluentd, Kibana) stack on a manually created Kubernetes cluster.

## Repository Structure

- `charts/` - Contains Helm charts for deploying Fluentd, Kibana, and Elasticsearch.
- `deployments/` - Kubernetes manifests for deploying Elasticsearch, Fluentd, and Kibana.
- `scripts/` - Contains setup scripts to apply Kubernetes configurations.
- `README.md` - This file.
- `values.yaml` - Configuration values for Helm charts.

## Getting Started

Follow these steps to deploy the EFK stack:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/faisalkamilansari/efk-deployment.git
   cd efk-deployment