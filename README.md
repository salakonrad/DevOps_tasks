
# DevOps_tasks

**1. k8s cluster**   
Required software on host: 
 - Vagrant  
 - Ansible

In case of usage Vagrant on MacOS system for k8s Installation use vagrant command with root privileges. This will allow Ansible to write temp file to Filesystem.
```
cd k8s-3node/
sudo vagrant up
```

**2. Docker LB**  
Required software on host:
- Docker
- docker-compose
