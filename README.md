# ansible-lab1

## Descrição
Este repositório possui todos playbooks necessários para instalação e configuração de um host web e monitoramento.

## computing
É o conjunto de playbooks do Ansible responsáveis por atualizar o sistema operacional, instalar o Docker, Docker-Compose e o node_exporter para coletar métricas de monitoramento.

**OBS:** Também inicia um container com Nginx na porta 80

## monitoring
É o conjunto de playbooks do Ansible responsáveis por criar os containers do Prometheus e do Grafana. Também efetua a configuração inicial para que exista um dashboard com informações dos hosts monitorados

