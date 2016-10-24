# ansible-postgresql
  
  This repo helps you in getting started with any postgresql test/dev environment for learning and praticing purpose.
  This should not be used directly on Production/Live system.
  
#### What this repo do ?
   - Creates three centos-7 VMS, using Vagrant
   - Install PostgreSQL and related packages using Vargrant ansible provisioning 
   - Start postgresql instances on the server 
 
```sh
git clone http://github.com/ashokraj/ansible-postgresql.git testapp
cd testapp
vagrant up 
vagrant status 
ansible-playbook -i .vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory initialized_pgdb.yml
```
