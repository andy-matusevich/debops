## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) salt

[![Travis CI](http://img.shields.io/travis/debops/ansible-salt.svg?style=flat)](http://travis-ci.org/debops/ansible-salt) [![test-suite](http://img.shields.io/badge/test--suite-ansible--salt-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-salt/) 

This role will install and configure [SaltStack](http://www.saltstack.com/)
master service, which can be used to manage Salt minions. By default, Salt
master packages from upstream repositories will be installed and configured
to listen on both IPv4 and IPv6 networks and will accept connections from
all hosts; you can limit connections through the firewall using
[debops.ferm](https://github.com/debops/ansible-ferm/) role.


### Role dependencies

- `debops.ferm`
- `debops.etc_services`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`salt` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
