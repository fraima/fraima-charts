### Lint the chart
```bash
helm lint helm-chart-sources/*
```


### Create the Helm chart package
```bash
helm package helm-chart-sources/*
```

### Create the Helm chart repository index
```bash
helm repo index --url https://helm.fraima.io/fraima-charts/ .

```

### Push the git repository on GitHub
```bash
git add . && git commit -m “Initial commit” && git push origin master

```