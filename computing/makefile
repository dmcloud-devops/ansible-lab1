deploy:
	ansible-playbook site.yml -i inventory \
	-e "system_deploy=true" \
	-e "docker_deploy=true" \
	-e "node_exporter_deploy=true"

deploy_with_web:
	ansible-playbook site.yml -i inventory \
	-e "system_deploy=true" \
	-e "docker_deploy=true" \
	-e "nginx_deploy=true" \
	-e "node_exporter_deploy=true" \
	-e "cadvisor_deploy=true"

deploy_only_docker:
	ansible-playbook site.yml -i inventory \
	-e "system_deploy=true" \
	-e "docker_deploy=true"

deploy_only_nginx:
	ansible-playbook site.yml -i inventory \
	-e "nginx_deploy=true"

deploy_only_agent_monitor:
	ansible-playbook site.yml -i inventory \
	-e "node_exporter_deploy=true" \
	-e "cadvisor_deploy=true"

update_so:
	ansible-playbook site.yml -i inventory \
	-e "system_deploy=true"
