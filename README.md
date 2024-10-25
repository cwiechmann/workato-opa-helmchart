# Workato On-Premise Agent Helm-Chart

The Workato On-Premise Agent is available for various platforms, including a Docker image. It’s natural to want to deploy this image not in isolation, but within a container orchestration platform like Kubernetes or OpenShift. Doing so offers several advantages, such as easier scaling, self-healing capabilities, and more.

A common method for deploying applications on Kubernetes environments is through Helm, and this project provides a Helm chart for deploying the On-Premise Agent.

## Setup

Please note that the Helm chart must be configured according to the specific Kubernetes environment. It is not intended for the Helm chart to be installed without local configuration. Therefore, create a local values file, for example: `dev_opa_values.yaml`, which contains the necessary configuration parameters. You local values files should be version controlled. Typical configuration include for example, the volume configuration.

The overall steps are the following:  
1. Clone the repository
2. Manage your local values files
3. Deploy the Helm-Chart using your local values file

### Clone the repository

### Manage your local values files

### Deploy the Helm-Chart
