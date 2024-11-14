# Helm Charts Repository

Welcome to the Helm Charts repository. This repository hosts Helm charts for various applications. You can add this repository to your Helm configuration with:

```bash
helm repo add kubikobot https://kubikobot.github.io/helm-charts
helm repo update
```

## Available Charts

- **top-funny-news-0.1.0** (version 0.1.0)
  - Description: A Helm chart for Kubernetes
  - Install: `helm install <release-name> kubikobot/top-funny-news-0.1.0 --version 0.1.0`

- **top-funny-news-0.1.4** (version 0.1.4)
  - Description: A Helm chart for Kubernetes
  - Install: `helm install <release-name> kubikobot/top-funny-news-0.1.4 --version 0.1.4`

## Usage Instructions
To install a chart, use the following command:

```bash
helm install <release-name> kubikobot/<chart-name> --version <version>
```
