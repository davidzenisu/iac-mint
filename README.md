# iac-mint
Setup scripts and ansible playbook to get a linux mint workstation up and running as quickly as possible.

## Quickstart

Run the following command in your bash shell:
```
wget -O - https://raw.githubusercontent.com/davidzenisu/devops-mint/main/setup.sh | bash
```
Alternatively, if there is an issue during the final step of running the Ansible playbook, you can simply run:
```
ansible-pull -k -i localhost, -c local -U https://github.com/davidzenisu/devops-mint.git playbook.yml
```
