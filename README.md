# HomeBox

An Helm chart to deploy [HomeBox](https://github.com/sysadminsmedia/homebox)

## Goal

This repo contains an helm chart to help deploying HomeBox on your Kubernetes cluster.

## Installation

Currently that helm-chart is not (yet) deployed to a helm-registry. So you have to install it by checking out this repo

```
$ git checkout https://github.com/nicolas2bonfils/helm-homebox.git
$ cd helm-homebox
$ helm install -n homebox homebox . -f values.yaml
```

