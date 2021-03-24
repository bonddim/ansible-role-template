# Ansible Role: {{ cookiecutter.namespace }}.{{ cookiecutter.role_name }}

[![Ansible Role](https://img.shields.io/ansible/role/<<ROLE_ID>>?label=galaxy&logo=ansible)](https://galaxy.ansible.com/{{ cookiecutter.namespace }}/{{ cookiecutter.role_name }})
[![Ansible Role Downloads](https://img.shields.io/ansible/role/d/<<ROLE_ID>>?logo=ansible)](https://galaxy.ansible.com/{{ cookiecutter.namespace }}/{{ cookiecutter.role_name }})
[![Ansible Quality Score](https://img.shields.io/ansible/quality/<<ROLE_ID>>?logo=ansible)](https://galaxy.ansible.com/{{ cookiecutter.namespace }}/{{ cookiecutter.role_name }})
[![Workflow](https://img.shields.io/github/workflow/status/{{ cookiecutter.namespace }}/ansible-role-{{ cookiecutter.role_name}}/Molecule?logo=github)](https://github.com/{{ cookiecutter.namespace }}/ansible-role-{{ cookiecutter.role_name }}/actions/workflows/molecule.yaml)
[![License](https://img.shields.io/github/license/{{ cookiecutter.namespace }}/ansible-role-{{ cookiecutter.role_name }})](https://github.com/{{ cookiecutter.namespace }}/ansible-role-{{ cookiecutter.role_name }}/blob/{{ cookiecutter.github_branch }}/LICENSE)

A brief description of the role goes here.

## Requirements
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## Dependencies
A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Role Variables
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Example Playbook
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
- hosts: servers
  roles:
    - { role: {{ cookiecutter.namespace }}.{{ cookiecutter.role_name }}, var: value }
```

## License
MIT

## Author Information
[{{ cookiecutter.author_name }}](https://github.com/{{ cookiecutter.namespace }})
