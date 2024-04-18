# vault-ha-cluster-playbook
An Ansible playbook to deploy a Vault HA cluster on VMs

1. Fill in the `inventory.yml` and `settings.yml` files 
2. Run the playbook with `ansible-playbook -i inventory.yml deploy.yml`
3. Get your Unseal or Recovery keys in the `keys.txt` file created in the repo root directory
