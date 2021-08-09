# Azure Arc App & Data Services Quickstart
This repo contains infrastructure-as-code automation scripts & templates to deploy an Azure Arc quickstart Hello World app. This quickstart highlights recently announced Azure Arc App Service & Data capabilities. The intention of this repo is to accelerate local App Service & Data on Arc enabled Kubernetes prototyping.

The set of scripts & templates in this repo do the following:
1. Create an Azure Arc connected Kubernetes cluster, either AKS or Docker Desktop single node clusters
1. Create Azure App Service and Azure Data services on top of the Arc connected Kubernetes cluster
1. Deploy & configure a Hello World web app on Arc App Service and connect to the Arc Data services backend, either SQL Managed Instance or PostgreSQL

## Prerequisites

- [Set up your Workstation](prerequisites.md)

## Deployment Scripts

- [Arc App Service + Arc SQL Managed Instance or PostgreSQL Hyperscale on AKS](deploying-arc-aks.md)
- [Arc App Service on local Docker Desktop](deploying-arc-appservice-ddk8s.md)

## Next Steps
Checkout Microsoft's [Azure Arc Jumpstart - ArcBox](https://azurearcjumpstart.io/azure_jumpstart_arcbox/). ArcBox is larger-scale Arc sandbox, enabling you to evaluate Azure Arc scenarios on a more "on-prem" production-like Kubernetes environment.
