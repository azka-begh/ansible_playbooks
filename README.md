# Ansible 

### AWSX Set Up
 [AWS](http://vcloud-lab.com/entries/devops/ansible-awx-tower-github-inventory-integration-github-inventory-source)

### Ansible CLI 
1. ansible-galaxy init role-name
2. ansible hostname -m module -a "options"
3. ansible-playbook playbook.yml
4. ansible-vault encrypt_string --vault-id name_of_id@password-file-name "string" --name "variable"
5. ansible-vault encrypt_string --vault-pass-file password-file-name "string" --name "variable"
6. ansible-playbook playbook.yml --ask-vault-pass
