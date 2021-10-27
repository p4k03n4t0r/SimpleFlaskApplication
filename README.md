# SimpleFlaskApplication

This repository contains an application that will be deployed via ArgoCD according to GitOps. The repository with the deployment can be found [here](https://github.com/p4k03n4t0r/gitops). This repository contains the CI of the application and triggers the CD by bumping the version of the application in the deployment of the other repository.

## Bump version in yaml

TODO: https://cloud.google.com/kubernetes-engine/docs/tutorials/gitops-cloud-build#modifying_the_continuous_integration_pipeline_to_trigger_the_continuous_delivery_pipeline