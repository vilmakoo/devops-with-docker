# Kubernetes, a container-orchestration system

#### What is Kubernetes?

Kubernetes is an open-source container-orchestration system. It is used for managing containerized workloads and services.

Kubernetes has a large and rapidly growing ecosystem and it is widely available.

Besides being a container-orchestration system, it also serves as a platform that enables building components and tools for deploying, scaling and managing applications automatically.

![kubernetes architecture](https://upload.wikimedia.org/wikipedia/commons/thumb/b/be/Kubernetes.png/800px-Kubernetes.png)

(Image from [here](https://en.wikipedia.org/wiki/File:Kubernetes.png).)

#### Why and when should one use it?

Kubernetes has a container-centric management environment that deploys containers based on operating-system-level virtualization instead of hardware virtualization which is a more traditional way.
One application can be packed in one container image which is beneficial because then those immutable container images can be created at build or release time instead of deployment time. This creates consistency.

Benefits of the container-centric management environment include e.g. agile application creation and deployment, continuous development/integreation/deployment,
observability, environmental consistency, cloud and OS distribution portability, application, centric management,
loosely coupled micro-services, and resource utilization.

In addition to the advantages of the container-centric management environment, Kubernetes helps the user by orchestrating computing, networking and storage infrastructure.
It offers the simplicity of Platform as a Service (PaaS) with flexibility of Infrastructure as a Service (IaaS) and it enables portability across infrastucture providers.

That being said, Kubernetes is not a traditional PaaS as it is not monolithic and operates at the container level and not at the hardware lever. Still, it does offer optional features that are common to PaaS offerings, for example deployment, scaling and load balancing.

There are some cases where you might want to consider some other solution than Kubernetes:

- If you need your code deployed and you application built by it.
- If you need application-level services.
- If you need it to dictate logging, monitoring and alerting solutions.
- If you want it to provide a configuration language or system.
- If you need it to provide comprehensive machine configuration, maintenance, managment or self-healing systems.

#### Summary

Kubernetes is a fine solution for automatic deployment scaling and management of multi-host systems as it puts in use a container-centric management environment, orchestrates computing, networking and storage infrastructure, and has a large variety of features.

(Sources used for this short article: [Wikipedia](https://en.wikipedia.org/wiki/Kubernetes) and [the Kubernetes documentation](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/).)