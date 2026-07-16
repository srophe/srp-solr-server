2026-07-16: Archiving this repository as no longer needed. Syriaca.org and related projects currently use the Gaddel application for publishing data, [srophe/Gaddel](https://github.com/srophe/Gaddel)

SRP Solr Deployment
===================

Requires: Ansible (and Vagrant to make a VM)

    $ pip install ansible
  
To begin:

    $ vagrant up
    $ ansible-playbook setup.yml -k -i setup_hosts

See: http://192.168.35.10:8983/solr/

