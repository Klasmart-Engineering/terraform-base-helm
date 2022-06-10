# KidsLoop Terraform Base Helm Chart

An helm chart that wraps around the terraform kubernetes operator

In order to use this helm chart, please make sure you supply your own `values.yaml` file.
The values in the `values.yaml` file in this repository are placeholders only and should
not be used in any environment.

## Publishing a new chart

```sh
helm package charts -d artifacts
```

## Upgrading an existing Release to a new major version

A major chart version change (like v1.2.3 -> v2.0.0) indicates that there is an
incompatible breaking change needing manual actions.

## Customizing the helm chart

Please see [values file](values.yaml) for all of the customization currently available
