Galera ansible playbook
=======================

This playbook installs a galera cluster on an openstack vm. Configure using the
var file in vars/ . Use `ansible-playbook site.yml -e "env=prod"` to run the
playbook with vars/prod.yml as the var file.
