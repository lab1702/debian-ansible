# debian-ansible

Ansible configuration that can be used with either Debian or Ubuntu.

## Complete Workstation Setup

### Ansible Commands

Run this once after installing the OS:

    sudo apt update && sudo apt install -y git ansible

Run this to apply the config to your workstation:

    sudo ansible-pull -U https://github.com/lab1702/debian-ansible.git --extra-vars "host_user=$USER"

## R

To install the R language, follow instructions at [https://cloud.r-project.org/bin/linux/ubuntu/](https://cloud.r-project.org/bin/linux/ubuntu/) to get latest versions.

## RStudio

To install RStudio Desktop, RStudio Server or Shiny Server, follow instructions at [https://posit.co/](https://posit.co/) to get latest versions.

## Snaps

After this is installed and rebooted, see [snap-ansible](https://github.com/lab1702/snap-ansible) to install Snap apps.
