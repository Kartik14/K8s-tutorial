# Kubernetes guide

This repository is the code for kubernetes course by [Stephen Grider on Udemy](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/).

# Notes

* In Kubernetes, we deploy objects through config files. Example of some objects are pods, services, StatefulSets etc
* Pods are used to deploy a single or multiple closely related containers
* Services are used for setting up networking configuratoin in the kubernetes cluster. There are 4 sub-types of Services: **ClusterIP, NodePort, LoadBalancer, Igris**
* NodePort Service is used to expose a pod(container) to outside world (meant for dev puposes)
* In k8s, **Nodes** are individual machines to run containers, **Masters** are machines with a set of programs to manage nodes
* Kubernetes does not build images, it pulls it from somewhere else. User also do not explictly handle container deployment and scheduling on nodes
* Master is constantly working to meet a **Desired state** as and when the user changes the state configuration


# Useful commands

* `kubectl apply -f <filename>` - change the current configuration of the kubernetes node with the given config file
* `kubectl get pods/services` - get running pods and services status