# debian-ansible

Ansible configuration that can be used with Debian 13.

## Complete Workstation Setup

### Run this as root once after installing the OS

    apt update && apt upgrade -y && apt install -y git ansible

### Run this as root to apply the config to your workstation

    ansible-pull --diff -U https://github.com/lab1702/debian-ansible.git

## Optional: Add yourself to sudo and docker groups

***Edit the username here to be your own***

    usermod -aG sudo lab
    usermod -aG docker lab

## Claude Code

    curl -fsSL https://claude.ai/install.sh | bash

## OpenCode

    curl -fsSL https://opencode.ai/install | bash

## Rust

    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

## NodeJS

*This is needed if you want to install NPM packages to your home directory.*

### Configure npm to install packages in user home directory

    mkdir ~/.npm-global
    npm config set prefix '~/.npm-global'
    echo 'export PATH=~/.npm-global/bin:$PATH' >> ~/.bashrc
    export PATH=~/.npm-global/bin:$PATH

## Artillery Load Tester

    npm install -g artillery@latest
