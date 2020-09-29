# Kubernetes Helm charts by kelvinwijaya

This is a [Helm](https://helm.sh) charts repository for Kubernetes for personal usage.

## Pre-build the chart metadata
```
#Generate the helm deployment templates and values into tar ball
helm package -d adminer ../helm-adminer
#Update the index.yaml
helm repo index --url https://kelvinwijaya.github.io/helm-charts/ .
```

### Add Helm repository

To install the Helm repo just run:

```bash
helm repo add kw https://kelvinwijaya.github.io/helm-charts
helm repo update
```

### Helm Charts

* [adminer](https://github.com/kelvinwijaya/helm-adminer)

  ```bash
  helm install --name your-release kelvinwijaya/adminer
  ```
