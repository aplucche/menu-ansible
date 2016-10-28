Setup
========
Ansible playbook that configures Go, Nginx, Supervisor, Git and npm

Run initial-setup.yml:

    ansible-playbook -s initial-setup.yml -u root --vault-password-file vault_pass.txt

Run deploy.yml:

    ansible-playbook -s deploy.yml
