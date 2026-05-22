# Nexoryx_GPU_Cluster

Production-ready GPU-enabled Kubernetes AI infrastructure platform with NVIDIA GPU Operator, Ollama, CUDA workloads, autoscaling, monitoring, and distributed AI compute support.

## Features

- NVIDIA GPU Operator
- GPU-enabled Kubernetes workloads
- CUDA runtime support
- Ollama GPU inference
- GPU autoscaling
- Prometheus monitoring
- Grafana dashboards
- Node Feature Discovery
- NVIDIA Device Plugin
- Persistent storage
- Ingress support
- Production-ready manifests

## Stack

- Kubernetes
- NVIDIA GPU Operator
- CUDA
- Ollama
- Docker
- Prometheus
- Grafana
- NGINX Ingress
- NVIDIA Container Toolkit

## Deployment

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-gpu
```

## Components

- GPU Operator
- GPU Device Plugin
- Ollama GPU Pods
- Prometheus
- Grafana
- Ingress
- Autoscaling

## Requirements

- NVIDIA GPU Nodes
- NVIDIA Drivers
- Kubernetes Cluster
- Helm installed
- NVIDIA Container Toolkit

## Notes

Update domains, storage classes, and GPU resource limits before production deployment.
