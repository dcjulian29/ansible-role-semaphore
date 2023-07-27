# Ansible Role: semaphore

[![Lint](https://github.com/dcjulian29/ansible-role-semaphore/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-semaphore/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-semaphore.svg)](https://github.com/dcjulian29/ansible-role-semaphore/issues)

This an Ansible role to install Semaphore's responsive web UI for running Ansible playbooks.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.semaphore
  src: https://github.com/dcjulian29/ansible-role-semaphore.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
