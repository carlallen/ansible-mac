<img src="https://raw.githubusercontent.com/geerlingguy/mac-dev-playbook/master/files/Mac-Dev-Playbook-Logo.png" width="250" height="156" alt="Mac Dev Playbook Logo" />

# Carls Mac Ansible Playbook

## Bootstrap
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/carlallen/ansible-mac/main/bootstrap.sh)"`


## Install Requirements
`ansible-galaxy install -r requirements.yml`

## Run Ansible
`ansible-playbook main.yml --ask-become-pass`


## Ruby Installation
`rvm install $(cat .ruby-version) --reconfigure --enable-yjit --with-openssl-dir=$(brew --prefix openssl@3)`