# Learning-Kubernetes

## What is Kubernetes?
- Kubernetes is an open source Container Orchestration tool.

### What is Container Orchestration??
Container Orchestration is a process of automatically managing and coordinating a large number containers. It manage task like
- **Starting and Stopping containers**
- **Placing containers on right machine**
- **Scaling containers up and down based on usage**
- **Restart containers on failures**

Kubernetes helps you manage containerized application in different environment like on-permise, Cloud, Hybrid setup. It ensures you application runs effectively, remain scalable, and are resilient to failures, without you having to manage containers manually.

## Why Kubernetes was developed??
Kubernetes was developed by Google and later open-sourced to help manage the complex challenges of deploying and running large-scale containerized applications. Before Kubernetes, Google used its internal system called Borg, which inspired Kubernetes.

### Need for Container Orchestration tool:
As Container adoption grew, so did the complexity for managing those containers. Here are few reasons why Kubernetes became essential:

1. **Manual Management is Inefficient**:
   Managing containers manually becomes overwhelming when there are hundreds or thousands of them running across multiple servers.

2. **Scaling**:
   Applications need to handle changing workloads. Orchestration tools automatically scale containers up or down based on demand.

3. **Load Balancing**:
   They distribute traffic evenly across containers to prevent overloading a few while others remain idle.

4. **High Availability**:
   Orchestration tools detect and restart failed containers, ensuring applications are always running.

5. **Resource Optimization**:
   Efficiently utilizes available hardware resources by placing containers on the best-fit servers.

6. **Environment Agnostic**:
   Orchestration tools abstract the underlying infrastructure, allowing you to run the same containerized application in development, testing, and production environments.

7. **Automation**:
   They automate tasks like container deployment, updates, rollbacks, and networking, saving time and reducing errors.


