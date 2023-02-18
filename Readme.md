# Final project

### Используемые технологии
- VirtualBox
- Ansible with galaxy repositories: 
    * community.docker
    * community.general
- Docker
   * registry
- Kubernetes. Microk8s with addons:
   * dns
   * ingress
   * rbac
   * metrics-server 
   * helm3
   * ha-cluster 
- CI:
  * Jenkins
  * Gitlab ci
- Monitoring
  * Prometheus
  * Grafana
  * Loki
  * Promtail


### Виртуальные машины:
1. git server (Располагается git server и docker registry)
2. Ansible vm
3. Jenkins master vm
4. Jenkins slave vm
5. Kubernetes vm
