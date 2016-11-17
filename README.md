# Ansible Role: List All Users

An Ansible role that lists all users on all servers.

## Role Variables

Available variables are listed below, along with default values:

    gather_facts: False

## Example Playbook

    - hosts: localhosts
      roles:
        - { role: SkinnyVans.list_all_users }
