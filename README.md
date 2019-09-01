# myrancherprivacy
Guilherme Oliveira, old 21 years \
My Ranchers Repository 😊

Informação sobre a primeira: v1.6.28 
#Release v1.6.28 
# Important:
This release addresses a security vulnerability found in Rancher versions v1.6.27 and earlier (Cattle and Kubernetes users). It affects the built-in node drivers having a file path option that allows the machine to read arbitrary files from inside the Rancher server container. This can result in the machine creator gaining unauthorized access to the Rancher server. You can view the official CVE here CVE-2019-12274 13.

- Versions:
rancher/server:v1.6.28 \ 
rancher/agent:v1.2.11 \
rancher/win-agent:v0.2.0 \  
rancher/lb-service-haproxy:v0.9.11 \ 
rancher-v0.6.13 \ 
rancher-compose-v0.12.5

- Supported Docker Versions:
Docker 1.12.3-1.12.6 e posteriores
