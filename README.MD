Install ansible for local machine
```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

ping
```
ansible all -m ping
```

setup
```
ansible-playbook setup.yml
ansible-playbook elasticstack.yml
ansible-playbook filebeat.yml
ansible-playbook postgresql.yml
ansible-playbook rabbitmq.yml
ansible-playbook nginx.yml
```
