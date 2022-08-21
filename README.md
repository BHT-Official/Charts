# B.H.T. Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add bht https://charts.bht.st
helm repo update
```

You can then run `helm search repo bht` to see the charts.

## Charts

* [wikibase](https://github.com/BHT-Official/Helm-Charts/tree/master/charts/wikibase)

### Wikibase

This chart is based on [wmde/wikibase-release-pipeline](https://github.com/wmde/wikibase-release-pipeline)

```bash
helm install --name wikibase wmde/wikibase-release-pipeline
```
