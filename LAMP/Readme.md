### This playbook will deploy a LAMP stack with an encrypted MySQL root password, providing a secure and organized way to set up your infrastructure.


* Now that your playbook and roles are set up, you can encrypt sensitive information using Ansible Vault:

   ```sh
     ansible-vault encrypt roles/mysql/vars/main.yml
   ```


* When you run the playbook, provide the vault password when prompted:

    ```sh
      ansible-playbook playbook.yml --ask-vault-pass
    ```
