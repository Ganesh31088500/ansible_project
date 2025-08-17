# ansible_project
Task 1:

#commands

pip install boto3


ansible-galaxy collection install amazon.aws


# Setup vault 
openssl rand -base64 2048 > vault.pass

ansible-vault create group_vars/all/pass.yml --vault-password-file vault.pass

ansible-playbook ec2_create.yml --vault-password-file vault.pass
 Task 2:
  password less authentication

  Task3 : shutdown the ubuntu 
