SRP Solr Deployment
===================

Requires: Ansible (and Vagrant to make a VM)

    $ pip install ansible
  
To begin:

    $ vagrant up
    $ ansible-playbook setup.yml -k -i setup_hosts

See: http://192.168.35.10:8983/solr/

