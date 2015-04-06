To reach the vagrant vm from the command-line:   
ansible-playbook -i .vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory --private-key=.vagrant/machines/dokuwiki_vm/virtualbox/private_key -u vagrant ansible/deploy.yaml
