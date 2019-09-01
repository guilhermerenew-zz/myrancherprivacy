# myrancherprivacy
Guilherme Oliveira, old 21 years \
My Ranchers Repository 😊

Informação sobre a primeira: v1.6.28 
# Release v1.6.28 
- Developing/Testing Rancher Server Container

The Rancher server container is comprised of multiple components (e.g. cattle, rancher-compose-executor, websocket-proxy). It is often more efficient to run rancher/server using a master branch of one of these sub components than it is to build a whole new release of rancher/server. One can use the rancher/server:master container to run different components pointing to specific branches (including master) of the component instead having it pointed to a specific released version.

# Release v2.0
- Rancher \
The majority of Rancher 2.x software runs on the Rancher Server. Rancher Server includes all the software components used to manage the entire Rancher deployment.

- The figure below illustrates the high-level architecture of Rancher 2.x. The figure depicts a Rancher Server installation that manages two Kubernetes clusters: one created by RKE and another created by Amazon EKS (Elastic Kubernetes Service).
