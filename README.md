[![Build Status](https://travis-ci.org/juju4/ansible-ipv6.svg?branch=master)](https://travis-ci.org/juju4/ansible-ipv6)
# Linux IPv6 ansible role

A simple ansible role to either harden, either disable ipv6 in linux systems.

## Requirements & Dependencies

### Ansible
It was tested on the following versions:
 * 1.9
 * 2.0

### Operating systems

Tested with vagrant on Ubuntu 14.04 or 16.04

## Example Playbook

Just include this role in your list.
For example

```
- host: all
  roles:
    - ipv6
```

## Variables

Nothing specific for now.

## Continuous integration

This role has a travis basic test (for github), more advanced with kitchen and also a Vagrantfile (test/vagrant).

Once you ensured all necessary roles are present, You can test with:
```
$ cd /path/to/roles/ipv6
$ kitchen verify
$ kitchen login
```
or
```
$ cd /path/to/roles/ipv6/test/vagrant
$ vagrant up
$ vagrant ssh
```

## Troubleshooting & Known issues


## License

BSD 2-clause
