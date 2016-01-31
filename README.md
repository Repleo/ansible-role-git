# Ansible Role: git server via https by nginx

[![Build Status](https://travis-ci.org/repleo/ansible-role-git.svg?branch=master)](https://travis-ci.org/repleo/ansible-role-git)

Ansible role for installing git and nginx for self hosted private repositories.

## Requirements


## Role Variables

Available variables are listed below, along with default values:

    virtual_host: git
    repos_path: /opt/repos/git

## Dependencies

 - bennojoy.nginx - Installs nginx server on virtual host named git.

## Example Playbook

    - hosts: servers
      roles:
        - { role: ansible-git-role }

## License

GPL v3 - (c) 2016, Repleo, Amstelveen

Author Information
------------------

Repleo, Amstelveen, Holland -- www.repleo.nl  
Jeroen Arnoldus (jeroen@repleo.nl)
