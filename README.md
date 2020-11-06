# ocs-ansible-roles

Collection of Ansible OCS roles

=== Setup your environment

----
subscription-manager repos --enable="rhel-7-server-ansible-2.7-rpms"
yum update ansible

subscription-manager repos --enable rhel-server-rhscl-7-rpms

yum install python27-python-pip
pip install -U setuptools
pip install --user openshift kubernetes
----

=== Running individual roles

----
ansible-playbook roles/<role-name>/apply/main.yaml
----
