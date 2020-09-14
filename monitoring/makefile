deploy:
	ansible-playbook site.yml -i inventory \
	-e "prometheus_deploy=true" \
	-e "grafana_deploy=true" \
	-e "grafana_create_datasource=true"

deploy_only_grafana:
	ansible-playbook site.yml -i inventory \
	-e "grafana_deploy=true" \

deploy_only_prometheus:
	ansible-playbook site.yml -i inventory \
	-e "prometheus_deploy=true"

deploy_dashboards:
	ansible-playbook site.yml -i inventory \
	-e "grafana_create_datasource=true"