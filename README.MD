## Playbook to install docker on Linux

Put hosts to docker_hosts group in inventory file and start playbook with: 
```
ansible-playbook install-docker.yml
```

## Playbook to manage docker compose

Put host to docker_controller group in inventory and start playbook
```
ansible-playbook start-service-compose.yml
```