# Ansible Role: Grub

[![Build Status](https://travis-ci.com/HadrienPatte/ansible-role-grub.svg?branch=master)](https://travis-ci.com/HadrienPatte/ansible-role-grub)

An Ansible Role that configures Grub.

## Requirements

None.

## Role Variables

* `grub_timeout`: Grub timeout, defaults to `10`

# Dependencies

None.

# Example Playbook

```yaml
- name: Configure Grub
  hosts: all
  roles:
    - hadrienpatte.grub
```

## License

MIT

## Author Information

Hadrien Patte [![PGP 0xFB500BB0](https://peegeepee.com/badge/orange/FB500BB0.svg)](https://peegeepee.com/FB500BB0)
