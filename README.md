
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Ubuntu-orange)
![DevOps](https://img.shields.io/badge/DevOps-Ready-blue)
![Automation](https://img.shields.io/badge/Automation-Enabled-blue)

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


## Project Roadmap

- [ ] Kubernetes Helm charts
- [ ] GitOps support
- [ ] CI/CD improvements
- [ ] Monitoring dashboards
- [ ] Multi-cloud support
- [ ] Security hardening

## GitHub Actions

This repository includes:
- Shell validation
- Markdown linting
- Terraform validation (where applicable)

## Example Deployments

See:
- examples/
- docs/

## Related Nexoryx Projects

This repository is part of the Nexoryx infrastructure ecosystem.
