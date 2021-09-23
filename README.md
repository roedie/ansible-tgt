This Ansible role will allow you to configure iSCSI Targets on specified
hosts using [tgt](http://stgt.sourceforge.net/) package. You can create and
remove specific iSCSI Targets without disrupting the connections of other
targets. Only targets that are unused will be modified during normal
operation.

### Info below is outdated!

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.tgt

### Documentation

More information about `debops.tgt` can be found in the
[official debops.tgt documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-tgt/docs/).


### Role dependencies

- `debops.ferm`
- `debops.secret`
- `debops.apt_preferences`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`tgt` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
