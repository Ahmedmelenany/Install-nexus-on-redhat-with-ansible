# Installing nexus on redhat 

- make sure ansible installed on host machine
# Make sure the two machines reach each other 

- ping ip-address

# Create pub and priv keys for ssh connectivity 

- ssh-keygen -t rsa 
- ssh-copy-id remote_user@ip-address

# Run the playbook 

- ansible-playbook playbook.yaml
