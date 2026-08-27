# Sarasavi Bookshop — Platform Infrastructure Services (`sarasavi-platform`)

This repository aggregates the Spring Cloud platform infrastructure services of the Sarasavi Bookshop Distributed System as Git submodules.

**Author**: S.K.M Ushan Gimhan  
**Student ID**: 241711098  
**Module**: ITS 2130 Enterprise Application Development  
**GCP Project ID**: `project-af908f5b-1cbf-40dc-9a7`

---

## Submodules Included

| Service | Repository URL | Port | Role / Description |
| :--- | :--- | :--- | :--- |
| **`sarasavi-config-server`** | [sarasavi-config-server](https://github.com/ushan-Gimhan/sarasavi-config-server.git) | `8888` | Spring Cloud Config Server backed by Git repo `sarasavi-configurations` |
| **`sarasavi-eureka-server`** | [sarasavi-eureka-server](https://github.com/ushan-Gimhan/sarasavi-eureka-server.git) | `8761` | Netflix Eureka Service Registry with Peer Replication |
| **`sarasavi-api-gateway`** | [sarasavi-api-gateway](https://github.com/ushan-Gimhan/sarasavi-api-gateway.git) | `8080` | Spring Cloud API Gateway (Routing, CORS, Service Discovery Load Balancing) |

---

## Cloning With Submodules

```bash
git clone --recurse-submodules https://github.com/ushan-Gimhan/sarasavi-platform.git
```
