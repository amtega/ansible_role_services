# Ansible services role

This is an [Ansible](http://www.ansible.com) role which manages services through the service module.

## Requirements

[Ansible 2.7+](http://docs.ansible.com/ansible/latest/intro_installation.html)

## Role Variables

A list of all the default variables for this role is available in `defaults/main.yml`.

## Filters

This role don't provide any.

## Modules

This role don't provide any.

## Tests

<!-- A description of the tests provided by the role should go here. For example: -->

The role provides these tests:

- `main.yml`: basic functionality test

## Dependencies

- [amtega.check_platform](https://galaxy.ansible.com/amtega/check_platform)
- [amtega.select_hostvars](https://galaxy.ansible.com/amtega/select_hostvars)

## Usage

<!-- Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too. For example: -->

This is an example playbook:

```yaml
---

- hosts: all
  roles:
    - role: thisrole
      thisrole_var1: value1
      thisrole_var2: value2
      thisrole_varN: valuen
```

## Testing

<!-- A description of how to run tests of the role if available. For example: -->

Tests are based on docker containers. You can setup docker engine quickly using the playbook `files/setup.yml` available in the role [amtega.docker_engine](https://galaxy.ansible.com/amtega/docker_engine).

Once you have docker, you can run the tests with the following commands:

```shell
$ cd thisrole/tests
$ ansible-playbook main.yml
```

## License

Copyright (C) 2019 AMTEGA - Xunta de Galicia

This role is free software: you can redistribute it and/or modify it under the terms of:

GNU General Public License version 3, or (at your option) any later version; or the European Union Public License, either Version 1.2 or – as soon they will be approved by the European Commission ­subsequent versions of the EUPL.

This role is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details or European Union Public License for more details.

## Author Information

- Daniel Sánchez Fábregas
