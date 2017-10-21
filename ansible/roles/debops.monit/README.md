## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) monit

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-monit.svg?style=flat)](https://travis-ci.org/debops/ansible-monit)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--monit-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-monit/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.monit-660198.svg?style=flat)](https://galaxy.ansible.com/debops/monit)


[Monit](https://mmonit.com/monit/) is a service monitoring daemon. It can be
used to monitor processes, files, system and remote hosts, and if necessary,
take configured actions when specific parameters change, like restarting
services and notifying the system administrator.

This role can be used to configure Monit on a host. It will automatically
detect selected services and configure checks for them.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

```Shell
ansible-galaxy install debops.monit
```

### Documentation

More information about `debops.monit` can be found in the
[official debops.monit documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-monit/docs/).


### Role dependencies

- `debops.ansible_plugins`
- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- Nick Janetakis | [e-mail](mailto:nick.janetakis@gmail.com) | [Twitter](https://twitter.com/nickjanetakis) | [GitHub](https://github.com/nickjj)
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).