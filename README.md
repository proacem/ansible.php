# Ansible Role: php

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.php.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.php) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-php-blue.svg)](https://galaxy.ansible.com/sbaerlocher/php)

## Description

Installation and configuration of PHP on Ubuntu.

## Installation

```bash
ansible-galaxy install sbaerlocher.php
```

## Requirements

None

## Role Variables

See 'defaults/main.yml'

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.php
```

## Changelog

### 1.0

* inital commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher