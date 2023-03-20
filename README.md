# openyurt-helm

OpenYurt components helm charts

[![Version](https://img.shields.io/badge/OpenYurt-v0.7.0-orange)](CHANGELOG.md)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Go Report Card](https://goreportcard.com/badge/github.com/openyurtio/openyurt)](https://goreportcard.com/report/github.com/openyurtio/openyurt)

</div>

This functionality is in beta and is subject to change. The code is provided as-is with no warranties. Beta features are not subject to the support SLA of official GA features.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add openyurt https://openyurtio.github.io/openyurt-helm
```

You can then run `helm search repo openyurt` to see the charts.

### Install `openyurt`

```shell
helm upgrade --install openyurt -n kube-system openyurt/openyurt
```

### Install `yurt-app-manager`

```shell
helm upgrade --install yurt-app-manager -n kube-system openyurt/yurt-app-manager
```

### Install `yurt-dashboard`

```shell
helm upgrade --install yurt-dashboard -n kube-system openyurt/yurt-dashboard
```

### Install `raven-agent`

```shell
helm upgrade --install raven-agent -n kube-system openyurt/raven-agent
```

## Contributing

The source code of all [OpenYurt](https://openyurt.io) community [Helm](https://helm.sh) charts can be found on Github: <https://github.com/openyurtio/openyurt-helm>
