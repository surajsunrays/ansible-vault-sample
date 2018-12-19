# ansible-vault-sample
This repo contains some sample file for using ansible-vault
## Use of ansible-vault
### Creating ansible-vault file to store credentails or some secret information
```
ansible-vault create vault-details.yml
```
Enter the password twice and check the output message

### Encrypting the existing file using ansible vault
```
ansible-vault encrypt vault-details.yml
```
Enter the password twice and check the output message

### Viewing the content of ansible-vault file using secret ansible-vault password
```
ansible-vault view vault-details.yml
```
Enter the ansible-vault password to processed
### Editing the content of ansible-vault file
```
ansible-vault edit vault-details.yml
```
Enter the ansible-vault password to processed

### Decrypting the ansible-vault file
```
ansible-vault decrypt vault-details.yml
```
Enter the ansible-vault password to processed

### Reset the ansible-vault password
```
ansible-vault rekey vault-details.yml
```
Enter old password once and then new password twice.

## -------------------------------------- END ----------------------------------------------
