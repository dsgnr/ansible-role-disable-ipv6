# Ansible Role: Disable IPv6

[![Build Status](https://travis-ci.org/dsgnr/ansible-role-disable-ipv6.svg?branch=master)](https://travis-ci.org/dsgnr/ansible-role-disable-ipv6)

This role disables ipv6 on a Linux device.

## Requirements

None

## Role Variables

None

## Example Playbook

    ---
    
    - hosts: all
      become: true
      roles:
        - disable-ipv6

## License

GNUv3
