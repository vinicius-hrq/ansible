# Ansible 

This playbook downloads and configures [Node_exporter](https://github.com/prometheus/node_exporter) as a service.

Node Exporter is a Prometheus exporter for hardware and OS metrics with pluggable metric collectors. It allows to measure various machine resources such as memory, disk and CPU utilization.

### Run
```
ansible-playbook playbook.yml -i hosts
```


