# phpenv-nginx-ansible-vagrant

## Requirement

- Vagrant box `centos6.5`

## Usage

    $ cd vagrant/
    $ vagrant up

## for CakePHP

Uncomment `for_cakephp` in `ansible/site.yml`.

## List Ansible tasks

    $ ansible-playbook ansible/site.yml -i vagrant/.vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory --list-tasks

