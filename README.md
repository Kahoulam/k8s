# [Kubernetes][overview]
簡稱 K8s, 可以用來管理 [cluster](#cluster).

--- 
## [Cluster][Cluster]

### 安裝 cluster 管理工具 [kubeadm][kubeadm]
- Installing a container runtime
    - If you don't specify a runtime, kubeadm automatically tries to detect an installed container runtime by scanning through a list of known endpoints.
    - Docker Engine does not implement the CRI which is a requirement for a container runtime to work with Kubernetes
- https://kubernetes.io/docs/setup/production-environment/container-runtimes/
    - You need to install a container runtime into each node in the cluster so that Pods can run there. This page outlines what is involved and describes related tasks for setting up nodes.
    - 

1. https://goo.gl/4yZVBK
2. https://booming-cave-448.notion.site/111-2-Kubernetes-k8s-by-0fddc66afb4a424386e25a93d46734aa 
3. https://www.youtube.com/watch?v=o6bxo0Oeg6o


<!-- 
## Cluster
node 的集合

### [Components][components]

### Control Plane Components
- kube-apiserver
- etcd
- kube-scheduler
- kube-controller-manager
- cloud-controller-manager

### Node Components
- kubelet
- kube-proxy
- Container runtime

### Addons
- DNS
- Web UI (Dashboard)
- Container Resource Monitoring
- Cluster-level Logging

## [Glossary][glossary] -->

[overview]: https://kubernetes.io/docs/concepts/overview/
[architecture]: https://kubernetes.io/docs/concepts/architecture/
[tools]: https://kubernetes.io/docs/tasks/tools/
[kubeadm]: https://kubernetes.io/docs/reference/setup-tools/kubeadm/

[components]: https://kubernetes.io/docs/concepts/overview/components/
[components-of-kubernetes]: https://d33wubrfki0l68.cloudfront.net/2475489eaf20163ec0f54ddc1d92aa8d4c87c96b/e7c81/images/docs/components-of-kubernetes.svg
[glossary]: https://kubernetes.io/docs/reference/glossary/

<!-- glossary -->
[API server]: # "Also known as:kube-apiserver
The API server is a component of the Kubernetes control plane that exposes the Kubernetes API. The API server is the front end for the Kubernetes control plane."

[Cluster]: https://kubernetes.io/docs/reference/glossary/?all=true#term-cluster

[Control Plane]: # "The container orchestration layer that exposes the API and interfaces to define, deploy, and manage the lifecycle of containers."

[kubelet]: # "An agent that runs on each node in the cluster. It makes sure that containers are running in a Pod."

[nodes]: https://kubernetes.io/docs/concepts/architecture/nodes/ "A node is a worker machine in Kubernetes."

[pod]: # "The smallest and simplest Kubernetes object. A Pod represents a set of running containers on your cluster."
  
