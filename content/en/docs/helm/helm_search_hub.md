---
title: "Helm Search Hub"
---

## helm search hub

search for charts in the Helm Hub or an instance of Monocular

### Synopsis


Search the Helm Hub or an instance of Monocular for Helm charts.

The Helm Hub provides a centralized search for publicly available distributed
charts. It is maintained by the Helm project. It can be visited at
https://hub.helm.sh

Monocular is a web-based application that enables the search and discovery of
charts from multiple Helm Chart repositories. It is the codebase that powers the
Helm Hub. You can find it at https://github.com/helm/monocular


```
helm search hub [keyword] [flags]
```

### Options

```
      --endpoint string      monocular instance to query for charts (default "https://hub.helm.sh")
  -h, --help                 help for hub
      --max-col-width uint   maximum column width for output table (default 50)
  -o, --output format        prints the output in the specified format. Allowed values: table, json, yaml (default table)
```

### Options inherited from parent commands

```
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   Group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         Username to impersonate for the operation
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### SEE ALSO

* [helm search](helm_search.md)	 - search for a keyword in charts

###### Auto generated by spf13/cobra on 29-Oct-2020