# install-docker-ansible on Ubuntu

 
1. Obtain the playbook
git clone https://github.com/do-community/ansible-playbooks.git
cd ansible-playbooks/docker_ubuntu1804

2. Customize Options
nano vars/default.yml
 

3.Run the Playbook
ansible-playbook  playbook.yml -kK
