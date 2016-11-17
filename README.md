# README.md
# Ansible Role: List All Users

An Ansible role that lists all users on all servers.

## Requirements

## Role Variables

Available variables are listed below, along with default values:

    gather_facts: False

## Dependencies

## Example Playbook

    - hosts: webservers
      roles:
        - { role: username.acme }
