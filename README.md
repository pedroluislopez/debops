## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) core

[![Travis CI](http://img.shields.io/travis/debops/ansible-core.svg?style=flat)](http://travis-ci.org/debops/ansible-core) [![test-suite](http://img.shields.io/badge/test--suite-ansible--core-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-core/) 

`debops.core` Ansible role takes care of variables that are shared among
different roles and are useful to keep in a central location. This is done by
leveraging functionality of [Ansible local
facts](https://docs.ansible.com/ansible/playbooks_variables.html#local-facts-facts-d)
stored on remote hosts to ensure that the variables are always evaluated by
Ansible, even when playbook is run with or without different sets of role tags.



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`core` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
