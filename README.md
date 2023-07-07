# debian-ansible

## Complete Workstation Setup

### Ansible Commands

Run this once after installing the OS:

    sudo apt update && sudo apt install -y git ansible

Run this to apply the config to your workstation:

    sudo ansible-pull -U https://github.com/lab1702/debian-ansible.git --extra-vars "host_user=$USER"

## RStudio

To install RStudio Desktop, RStudio Server or Shiny Server, follow instructions at [https://posit.co/](https://posit.co/) to get latest versions.

# Snaps

After this is installed and rebooted, see [snap-ansible](https://github.com/lab1702/snap-ansible) to install Snap apps.