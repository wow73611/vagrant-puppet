# ansible-role-puppet

This ansible role that installs Puppet on Linux.


## Requirements

This role was developed using Ansible 2.2.3 Backwards compatibility is not guaranteed.
Use `ansible-galaxy install wow73611.puppet` to install the role on your system.


## Role Variables

This role has multiple variables. The defaults for all these variables are the following:

```yaml
---

```

## Dependencies

None

## Example Playbook

This is a sample playbook file for deploying the Ansible Galaxy puppet role.

```yaml
---
- hosts: all
  become: true
  roles:
    - role: wow73611.puppet
```


## License

MIT / BSD


## Resources

Puppetlabs repo install: [https://puppet.com/docs/puppet/5.5/puppet_platform.html](https://puppet.com/docs/puppet/5.5/puppet_platform.html)


## Author Information

This role was created in 2019 by [wow73611](https://github.com/wow73611/).

