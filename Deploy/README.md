# Prerequisite before running ansible playbook:

1) Provide the required input in var.yml

2) Provide the host address of server where you want to run the ansible playbook in the hosts file

3) Command to run the playbook:

[If using key based authentication]

ansible-playbook -i hosts deploy.yml -u "username" --private-key="private_key_path"

[If using password password authentication]

ansible-playbook -i hosts deploy.yml -u "username" -k
