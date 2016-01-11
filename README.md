# Ansible Role: Git

[![Build Status](https://img.shields.io/travis/rwanyoike/ansible-role-git.svg)](https://travis-ci.org/rwanyoike/ansible-role-git) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/rwanyoike/ansible-role-git/master/LICENSE)

Installs and configures Git on RHEL/CentOS ~~or Debian/Ubuntu~~.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
# This space intentionally left blank.
```

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers

  vars_files:
    - vars/main.yml

  roles:
    - role: rwanyoike.git
```

Inside `vars/main.yml`:

```yaml
git_packages:
  - git
  - git-svn

# ... etc ...
```

## License

MIT

## Author Information

- This role was created in 2014 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).
- This role was forked in 2015 by [Raymond Wanyoike](https://github.com/rwanyoike).
