### Defending Modern DevOps Environments 

This repository contains all of the labs for the Manicode "Defending Modern DevOps Course"

# Agenda:
001-Lab-Setup

002-Containerizing-An-Application

003-K8S-Cluster-Setup

004-K8S-Cluster-Authentication

005-K8S-Dashboard

006-Pod-Security-Policy

007-Istio

008-K8S-Cluster-Secrets

009-Kube-Logs

010-Security-Pipeline

DEMO-Attacking-Kubelet

Finale

## Useful Debugging Commands
```
minikube logs
kubectl get logs <podname>
kubectl exec -it <podname> /bin/bash
kubectl describe pod|service|deployment <name> 
kubectl get secret <secretname> 
kubectl get events | grep <thething>
kubectl create --v 10 -f .
```