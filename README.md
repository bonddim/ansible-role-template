# Ansible roles template (skeleton)

## Requirements
[cookiecutter](https://pypi.org/project/cookiecutter/)
```
python3 -m pip install cookiecutter
```

## Usage
Run cookiecutter and provide answers for questions
```
cookiecutter https://github.com/bonddim/ansible-role-template
```
For the role name question enter a value without the ansible-role- prefix

You can create `~/.cookiecutterrc` file and paste default values
```
default_context:
  author_name: First Last
  namespace: github_repo_owner
  github_branch: master
```

Replace *<<ROLE_ID>>* in README.md by the id value from galaxy

To get galaxy's role id:
```bash
ansible-galaxy info namespace.role_name | grep '\bid'
```
