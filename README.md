# Ansible Python

*This ansible role is created and maintained by [Media Pop](https://www.mediapop.co), a software consultancy. Hire us to resolve your DevOps challenges.*

[![Travis](https://travis-ci.org/mediapop/ansible-python.svg?branch=master)](https://travis-ci.org/mediapop/ansible-python)

Install other versions of python and set them as the default.

## Role Variables

```yml
python_alternative_version: "3.6"
python_pip_version: "20.2.2"
```

## Example Playbook

```yml
- hosts: webservers
  roles:
    - role: mediapop.python
```

## No module named apt_pkg

You can't use these alternative pythons with ansible always because it uses a package provided by `python3-apt`. [Set the ansible runtime python](http://docs.ansible.com/ansible/latest/python_3_support.html) with `ansible_python_interpreter: /usr/bin/python3.5` in the inventory or the playbook.
