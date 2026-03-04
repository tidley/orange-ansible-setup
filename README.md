# orange-ansible-setup

Ansible playbook to replicate my baseline setup:
- installs git/curl/gh/node/npm
- creates OpenClaw workspace folders
- seeds IDENTITY.md, USER.md, MEMORY.md
- clones/updates `friendpub`

## Run

```bash
cd orange-ansible-setup
ansible-playbook playbook.yml -K
```

`-K` prompts for sudo password.
