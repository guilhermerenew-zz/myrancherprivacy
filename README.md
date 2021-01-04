# 2021 Update LetsGo! :tada:
## myrancherprivacy

### Rancher 2.x

Rancher was originally built to work with multiple orchestrators, and it included its own orchestrator called Cattle. With the rise of Kubernetes in the marketplace, Rancher 2.x exclusively deploys and manages Kubernetes clusters running anywhere, on any provider.

Rancher can provision Kubernetes from a hosted provider, provision compute nodes and then install Kubernetes onto them, or import existing Kubernetes clusters running anywhere.

One Rancher server installation can manage thousands of Kubernetes clusters and thousands of nodes from the same user interface.

Rancher adds significant value on top of Kubernetes, first by centralizing authentication and role-based access control (RBAC) for all of the clusters, giving global admins the ability to control cluster access from one location.

It then enables detailed monitoring and alerting for clusters and their resources, ships logs to external providers, and integrates directly with Helm via the Application Catalog. If you have an external CI/CD system, you can plug it into Rancher, but if you don’t, Rancher even includes a pipeline engine to help you automatically deploy and upgrade workloads.

Rancher is a complete container management platform for Kubernetes, giving you the tools to successfully run Kubernetes anywhere.

### Release v2.0
- About \
The majority of Rancher 2.x software runs on the Rancher Server. Rancher Server includes all the software components used to manage the entire Rancher deployment.

- The figure below illustrates the high-level architecture of Rancher 2.x. The figure depicts a Rancher Server installation that manages two Kubernetes clusters: one created by RKE and another created by Amazon EKS (Elastic Kubernetes Service).

### Release v1.6.28 
- Developing/Testing Rancher Server Container \
The Rancher server container is comprised of multiple components (e.g. cattle, rancher-compose-executor, websocket-proxy). It is often more efficient to run rancher/server using a master branch of one of these sub components than it is to build a whole new release of rancher/server. One can use the rancher/server:master container to run different components pointing to specific branches (including master) of the component instead having it pointed to a specific released version.
