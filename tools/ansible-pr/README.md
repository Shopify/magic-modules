# Ansible PR Script
This is a Ruby script that creates a series of PRs from  the `build/ansible`
folder to ansible/ansible.

Pull Requests are made from the origin remote to Ansible core.
By default, the origin remote points to MM's version of Ansible

## Requirements
* `hub` CLI
* `build/ansible` has the origin remote to whatever fork of ansible
  you want PRs to appear as coming from (usually, your personal fork)