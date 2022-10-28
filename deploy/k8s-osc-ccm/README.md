# osc-cloud-controller-manager

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![AppVersion: 0.1.0](https://img.shields.io/badge/AppVersion-0.1.0-informational?style=flat-square)

A Helm chart for OSC CCM cloud provider

**Homepage:** <https://github.com/outscale-dev/cloud-provider-osc/>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| 3DS Outscale | <support@outscale.com> |  |

## Source Code

* <https://github.com/outscale-dev/cloud-provider-osc/>

## Requirements

Kubernetes: `>=1.14.0-0`

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| image.pullPolicy | string | `"IfNotPresent"` | Container pull policy |
| image.repository | string | `"outscale/cloud-provider-osc"` | Container image to use |
| image.tag | string | `"v0.1.0"` | Container image tag to deploy |
| imagePullSecrets | list | `[]` | Specify image pull secrets |
| oscSecretName | string | `"osc-secret"` | Secret name containing cloud credentials |
| podLabels | object | `{}` | Labels for pod |
| replicaCount | int | `1` | Number of replicas to deploy |
| verbose | int | `5` | Verbosity level of the plugin |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)