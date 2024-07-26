# openyurt-helm

OpenYurt components helm charts

[![Version](https://img.shields.io/badge/OpenYurt-v1.3.0-orange)](CHANGELOG.md)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Go Report Card](https://goreportcard.com/badge/github.com/openyurtio/openyurt)](https://goreportcard.com/report/github.com/openyurtio/openyurt)

**IMPORTANT: Starting from OpenYurt v1.5.0, The following Helm charts have been relocated to the [openyurtio/charts](https://github.com/openyurtio/charts) repository.**

- yurt-manager
- yurthub
- yurt-iot-dock
- yurt-coordinator
- raven-agent

We recommend that end users obtain these Helm Charts from [openyurtio/charts](https://github.com/openyurtio/charts) repository. Please note that this repository will be archived in future releases.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add openyurt https://openyurtio.github.io/openyurt-helm
```

You can then run `helm search repo openyurt` to see the charts.

### Install `yurt-manager`

```shell
helm upgrade --install yurt-manager -n kube-system openyurt/yurt-manager
```

### Install `yurthub`

```shell
helm upgrade --install yurthub -n kube-system openyurt/yurthub
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
