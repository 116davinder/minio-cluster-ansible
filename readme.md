# Minio Cluster Setup Using Ansible


## Notes*
```
Minimum Number of Nodes : 4
Maximum Number of Nodes : 16
```
## Requirements
* vagrant

## TO RUN
* **STEP-1**
```
vagrant up
```

* **STEP-2**
```
vagrant ssh controller
```

* **STEP-3**
```
cd /home/vagrant/projects/playbooks
```

* **STEP-4**
```
ansible-playbook -i hosts/cluster-hosts.ini cluster-setup.yml
```
# Supported/Tested OS
* CentOS/7
