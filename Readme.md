# Kubernetes guide

This repository is the code for kubernetes course by [Stephen Grider on Udemy](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/).

# Notes

* In kubernetes, we deploy objects through config files. Example of some objects are pods, services, StatefulSets etc
* Pods are used to deploy a single or multiple closely related containers
* Services are used for setting up networking configuratoin in the kubernetes cluster. There are 4 sub-types of Services: **ClusterIP, NodePort, LoadBalancer, Igris**

# Useful commands

* `kubectl apply -f <filename>` - change the current configuration of the kubernetes node with the given config file
* `kubectl get pods/services` - get running pods and services status