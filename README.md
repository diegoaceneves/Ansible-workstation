# Ansible-workstation
Ansible playbook to configure my Workstation


## Ansible Clean Install

```bash
python -m venv .venv
source .venv/bin/activate
pip install ansible
```

## Running

```bash
ansible-playbook -e @./host-var/<varfile>.yml -K -i hosts main.yml
```