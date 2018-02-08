# Ansible Python

*This ansible role is created and maintained by [Media Pop](https://www.mediapop.co), a software consultancy. Hire us to resolve your DevOps challenges.*

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
