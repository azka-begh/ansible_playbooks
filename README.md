#ansible

ansible-galaxy init role-name

ansible hostname -m module -a "options"

ansible-playbook playbook.yml

ansible-vault encrypt_string --vault-id name_of_id@password-file-name "string" --name "variable"

ansible-vault encrypt_string --vault-pass-file password-file-name "string" --name "variable"

ansible-playbook playbook.yml --ask-vault-pass
