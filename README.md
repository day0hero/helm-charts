# Helm Chart Repository

[argo-rollouts](./charts/argo-rollouts)

[rollout-canary](./charts/rollout-canary)

[rollout-bluegreen](./charts/rollout-bluegreen)


## Usage

Install helm on your machine using the [official docs](https://helm.sh/docs/intro/install/)

```shell
helm repo add https://day0hero.github.io/helm-charts/
```
```shell
helm search repo day0hero
```
```shell
helm install vp-hello day0hero/vp-hello
```

```shell
helm uninstall vp-hello
```
