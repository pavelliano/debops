## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) libvirtd

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-libvirtd.svg?style=flat)](https://travis-ci.org/debops/ansible-libvirtd)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--libvirtd-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-libvirtd/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.libvirtd-660198.svg?style=flat)](https://galaxy.ansible.com/debops/libvirtd)


The `debops.libvirtd` Ansible role manages the [libvirtd][libvirt]
daemon on a virtualization host (server side). It will automatically
install QEMU KVM support on any host that is not a KVM guest, to allow for
easy deployment of KVM virtual machines.

Configuration of `libvirtd` instance (local or remote) can be performed using
`debops.libvirt` role, which uses the `libvirt` API to manage the server.

[libvirt]: https://libvirt.org/

### Installation

This role requires at least Ansible `v2.2.3`. To install it, run:

```Shell
ansible-galaxy install debops.libvirtd
```

### Documentation

More information about `debops.libvirtd` can be found in the
[official debops.libvirtd documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-libvirtd/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)
- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) | [e-mail](mailto:ypid@riseup.net) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
