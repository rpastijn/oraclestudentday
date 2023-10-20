# Get started with Arm based Kubernetes clusters in Oracle Cloud Infrastructure

Estimated time: 45 minutes

## Introduction

This tutorial explains how to create Arm based Kubernetes clusters that use the Ampere A1 compute platform in Oracle Cloud Infrastructure(OCI). You will also deploy the popular web container, Apache Tomcat on the kubernetes cluster. 

Using the methods in this tutorial, you can create application deployments that are seamlessly portable between the Arm based kubernetes clusters and x86(Intel and AMD) based clusters. 

### Objectives

In this tutorial, you will:

* Create a Kubernetes cluster (OKE) powered by the Ampere A1 compute.
* Deploy Apache Tomcat to the cluster.
* Create deployments that are seamlessly portable across x86 and Arm based kubernetes clusters.  
* Deploy Java applications and micro services to the Tomcat web container.  

## What is the Ampere A1 Compute Platform

The Ampere A1 compute platform based on Ampere Altra CPUs represent a generational shift for enterprises and application developers that are building workloads that can scale from edge devices to cloud data centers. The unique design of this  platform delivers consistent and predictable performance as there are no resource contention within a compute core and offers more isolation and security. This new class of compute shapes on Oracle Cloud Infrastructure  provide an unmatched platform that combines power of the Altra CPUs with the security, scalability and eco-system of services on OCI.

### Prerequisites

1. An Oracle Cloud account

Optionally:

1. [Familiarity with OCI console](https://docs.us-phoenix-1.oraclecloud.com/Content/GSG/Concepts/console.htm)
1. [Overview of Networking](https://docs.us-phoenix-1.oraclecloud.com/Content/Network/Concepts/overview.htm)
1. [Familiarity with Compartments](https://docs.us-phoenix-1.oraclecloud.com/Content/GSG/Concepts/concepts.htm)
1. Basic conceptual knowledge of containers and Kubernetes

## Acknowledgements

* **Author** - Jeevan Joseph
* **Contributors** -  Orlando Gentil, Jeevan Joseph
* **Adopted for Oracle Student Day - Robert Pastijn
* **Last Updated By/Date** - Robert Pastijn, October 2023
