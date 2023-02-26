# KPMG-Test

Challenge-1:

To deploy MediaWiki on Docker/K8/OpenShift, we can follow the following steps:

IAC will be deployed through Terraform.

Create a Dockerfile for MediaWiki application.
Deploy the application on K8/OpenShift using a deployment configuration.

The whole setup is deployed on Azure Kubernetes Service and respective Managed Identities for pulling images from ACR via kubelet,RG etc will be created for AKS setup.
For automate CI/CD process, here we are using Jenkins for setting up the pipeline for CI/CD.
