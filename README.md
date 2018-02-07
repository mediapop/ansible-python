# Ansible Python

*Created by [Media Pop](https://www.mediapop.co), a software consultancy, reach out to solve your DevOps challenges.*

[![Travis](https://travis-ci.org/mediapop/ansible-python.svg?branch=master)](https://travis-ci.org/mediapop/ansible-python)

Install other versions of python and set them as the default.

## Role Variables

```yml
python_alternative_version: "3.6"
```

## Example Playbook

```yml
- hosts: webservers
  roles:
    - role: mediapop.python
```
