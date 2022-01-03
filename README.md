# Krush.Cloud Helm Charts

## ArgoCD Usage

*TODO*

## Local Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
  helm repo add krush-cloud https://krush-cloud.github.io/helm
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
krush-cloud` to see the charts.

To install the krush-env chart:

    helm install krush-env-dev krush-cloud/krush-env

To uninstall the chart:

    helm delete krush-env-dev