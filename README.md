# Ansible Role: CentOS 7 Kubernetes Services
[![GitHub Open Issues](https://img.shields.io/github/issues/million12/ansible-role-centos-kubernetes.svg)](https://github.com/million12/ansible-role-centos-kubernetes/issues)
[![GitHub Stars](https://img.shields.io/github/stars/million12/ansible-role-centos-kubernetes.svg)](https://github.com/million12/ansible-role-centos-kubernetes)
[![GitHub Forks](https://img.shields.io/github/forks/million12/ansible-role-centos-kubernetes.svg)](https://github.com/million12/ansible-role-centos-kubernetes)
[![GitHub release](https://img.shields.io/github/release/million12/ansible-role-centos-kubernetes.svg)](https://github.com/million12/ansible-role-centos-kubernetes)
[![license](https://img.shields.io/github/license/million12/ansible-role-centos-kubernetes.svg?maxAge=2592000)](https://github.com/million12/ansible-role-centos-kubernetes/blob/master/LICENSE)

---

Ansible role installs Kubernetes services on CentOS 7.


### Requirements
Tested on CentOS 7.

### Example Playbook

    - hosts: servers
      roles:
         - { role: million12.centos-kubernetes, tags: ['kube'] }


---
### Author

Author: Przemyslaw Ozgo (<przemek@m12.io>)

---
**Sponsored by [Prototype Brewery](http://prototypebrewery.io/)** - the new prototyping tool for building highly-interactive prototypes of your website or web app. Built on top of [Neos CMS](https://www.neos.io/) and [Zurb Foundation](http://foundation.zurb.com/) framework.
