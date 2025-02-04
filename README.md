# TRDP Helm Charts

## Adding the Helm Repository

```sh
helm repo add test-repo http://charts.martake.com
helm repo update

## Installing the Example Chart
helm install test-release test-repo/example