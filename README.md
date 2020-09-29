# Kubernetes Helm charts by kelvinwijaya

This is a [Helm](https://helm.sh) charts repository for Kubernetes for personal usage.

## Pre-build the chart metadata
```
#Point to (e.g. helm-adminer is the chart repository source code)
helm package -d adminer ../helm-adminer
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
