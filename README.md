# KubikoBot Helm Charts for any Kubernetes
A collection of Helm charts

## Goal

This repository holds the index file for [the Kubiko Helm Repository](https://kubikobot.github.io), served using
[GitHub pages](https://pages.github.com/). The index file serves to hold the list of available helm charts distributed or configured
by Kubiko, including the associated metadata that describes the charts. You can read more about the repository index
file from the [official documentation](https://helm.sh/docs/developing_charts/#the-index-file).

This repo is intended to be an opinionated view on packaging applications with Helm


## Installation

The Helm repository can be installed as follows:

```console
helm repo add kubiko https://kubikobot.github.io/helm-charts
```

You can then run `helm search repo kubikobot` to search for existing charts.

## Documentation

Documentation can be found [here](https://kubikobot.github.io/helm-charts/docs/).

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md)

## License

[GNU GENERAL PUBLIC LICENSE V3](./LICENSE)
