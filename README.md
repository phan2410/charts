## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```shell
helm repo add phan https://phan2410.github.io/charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo phan` to see the charts.

To install the phan/dummy-service chart:

```shell
helm install dummy-service phan/dummy-service
```

To uninstall the chart:

```shell
helm delete dummy-service
```