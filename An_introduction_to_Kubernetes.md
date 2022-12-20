# Chapter 2: An Introduction to Kubernetes

Kubenetes Walkthrough

![Logo](./pics/eks_product_page.png)

This chapter will introduce you to the basic workings of Kubernetes, This is mandatory if you are new to Kubernetes

### We will walk you through the below important topics

#### Kubernetes (k8s) Basics
#### Kubernetes Architecture
#### Amazon EKS

## Content

You may click on the below chapters to jump on that

- [Workshop Introduction](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/workshop_introduction.md)
- [An Introduction To Kubernetes](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/An_introduction_to_Kubernetes.md)
- [Setting up The Workshop Environment](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/Setting_up_the_Workshop_environment.md)
- [A Terraform Introduction & Primer for those unfamiliar with Terraform](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/_primer_for_those_unfamiliar_with_Terraform.md)
- [Building a private EKS cluster with Terraform](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/Building_a_private_EKS_cluster_with_Terraform.md)
- [Extra optional activities](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/Extra_optional_activities/md)
- [Conclusion](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/Conclusion.md)
- [Cleanup](https://github.com/CloudStrategyOfficial/workshop-aws-eks-terraform/blob/main/Cleanup.md)


## Kubernetes Basics

### What is Kubernetes

- Open source container management platform
- Helps you to run your container at scale
- Provides Objects and APIs for building modern applications

### Kubernetes Nodes

- Machines (Servers) utilizes kubernetes cluster, called Nodes
- Nodes in a Kubernetes cluster may be physical, or virtual.

#### There are two types of nodes:

- A Control-plane-node type, which makes up the Control Plane, acts as the “brains” of the cluster.
- A Worker-node type, which makes up the Data Plane, runs the actual container images (via pods).


### K8s Objects Overview

Kubernetes objects are entities that are used to represent the state of the cluster.
Object: “record of intent” – once created, the cluster does its best to ensure it exists as defined. This is known as the cluster’s “desired state.”
Kubernetes is always working to make an object’s “current state” equal to the object’s “desired state.” A desired state can describe:

- What pods (containers) are running, and on which nodes
- IP endpoints that map to a logical group of containers
- How many replicas of a container are running
And much more…

### K8s Objects Detail (1/2)
### K8s Objects Detail (2/2)
