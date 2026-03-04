# orange-ansible-setup

Ansible playbook to replicate core baseline setup:
- installs git/curl/gh/node/npm
- creates OpenClaw workspace folders
- seeds IDENTITY.md, USER.md, MEMORY.md
- does **not** include app repos or any private keys/secrets

## Run

```bash
cd orange-ansible-setup
ansible-playbook playbook.yml -K
```

`-K` prompts for sudo password.
