# ansible-playbooks
A collection of ansible playbooks. Each playbook has comments specifying variables which must be changed and special instructions.

### vagrant: LAMP stack, ubuntu/trusty64
Deploys a LAMP stack on an ubuntu/trusty64 vagrant box. The playbook does the following:

1. Update and upgrade the system
2. Install apache, mysql-server and PHP5
3. Start apache and mysql
4. Create a mysql user
5. Create a test database

The provided Vagrantfile will provision the box:
```
vagrant up --provision
```
The box will serve on 192.168.33.10 to the host machine only.
