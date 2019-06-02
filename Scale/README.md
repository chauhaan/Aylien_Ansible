# Prerequisite before running playbook:

1) Provide the required input in var.yml with the instance id of application server.

2) Provide the host address of server where you want to run the ansible playbook in the hosts file

3) Command to run the playbook:

[If using key based authentication]

ansible-playbook -i hosts scale.yml -u "username" --private-key="private_key_path"

[If using password password authentication]

ansible-playbook -i hosts scale.yml -u "username" -k
