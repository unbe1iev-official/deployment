# Kubernetes Server Deployment

Configuration for deploying a Kubernetes server with various components such as Harbor, Cosign, Keycloak, and Nginx-Ingress.

## IMPORTANT!
Please ensure that all security credentials and sensitive data are handled securely in a production environment. Remote resources have deliberately changed credentials.

## Components
- **Keycloak:** v24.0.4 Deployment
- **Harbor:** v2.10.2 Deployment
- **Cosign:** (latest/07/06/2024) v2.4.2 Deployment
- **Nginx, Ingress** Configs

### Keycloak
Keycloak is an open-source identity and access management solution for modern applications and services.

### Harbor & Cosign
Harbor is an open-source cloud-native registry that stores, signs, and scans container images for vulnerabilities.

### Nginx-Ingress
Nginx-Ingress is an Ingress controller for Kubernetes using NGINX as a reverse proxy and load balancer.
