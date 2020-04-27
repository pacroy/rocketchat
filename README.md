# Rocket.Chat Helm Chart

## Local Installation

```sh
helm install <release_name> . --namespace=<namespace> --set appHost=<www.yourdomain.com>
```

## Installation from Repository

```sh
helm repo add pacroy https://raw.githubusercontent.com/pacroy/helm-repo/master
```

```sh
helm repo update
```

```sh
helm install <release_name> pacroy/rocketchat --namespace=<namespace> --set appHost=<www.yourdomain.com>
```