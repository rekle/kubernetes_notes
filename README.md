# Kubernetes Notes

This project contains various notes, cheatsheets etc. related to Kubernetes

## Links

* [Kubernetes](https://kubernetes.io) - Project homepage
* [K9S](https://k9scli.io) - Text based GUI (free)
* [Lens](https://k8slens.dev) - Graphical UI (commercial)

## Cheatsheet

### Common Kubectl Command Line Options

You can use 'kubectl options' to list common command line options.

| Command | Description |
|---|---|
| --namespace=NAMESPACE | List only results in the namespace NAMESPACE |
| --all-namespaces | List results for all namespaces |
| --output=yaml | List command output as YAML |
| --output=json | List command output as JSON |
| --help | Append to a kubectl command to get help on it |


### Contexts

| Command | Description |
|---|---|
| kubectl config current-context | List the currently selected context |
| kubectl config get-contexts | List the currently configured contexts |
| kubectl config use-context NAME | Switch to the context named NAME |
| kubectl config set-context --current --namespace=NAMESPACE | Set the default namespace to to use when not specified to NAMESPACE |

### Deployments
| Command | Description |
|---|---|
| kubectl get deployments | List all deployments in the current namespace |

### Nodes
| Command | Description |
|---|---|
| kubectl get nodes | List all the current cluster nodes |

