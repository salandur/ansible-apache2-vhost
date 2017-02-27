salandur.apache2-vhost
============

[![Build Status](https://travis-ci.org/salandur/ansible-apache2-vhost.svg?branch=master)](https://travis-ci.org/salandur/ansible-apache2-vhost)

Ansible role to manage Apache2

### Example:

```yaml
- hosts: all

  roles:
    - salandur.apache-vhost
  vars:
    - vhost_domainname: test.example.com
```

### Variables

```yaml
vhost_domainname: text.example.com
```

The role will fail when the 'vhost_domainname' is not set.

### License

Licensed under the MIT License. See the LICENSE file for details.
