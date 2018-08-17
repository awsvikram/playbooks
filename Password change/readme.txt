Encrypt the pass.yml using ansible-vault and save the key in pass.txt file.
use the below command to update the password across multiple host

ansible-playbook Changepassword.yml -i inventory --vault-password-file pass.txt
