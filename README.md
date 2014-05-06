Stouts.foundation
=================

[![Build Status](https://travis-ci.org/Stouts/Stouts.foundation.png)](https://travis-ci.org/Stouts/Stouts.foundation)

Ansible role which contains the other common roles for setup new debian based machine

#### Requirements & Dependencies

- https://github.com/Ansibles/generic-users
- https://github.com/Ansibles/build-essential
- https://github.com/Ansibles/apt
- https://github.com/Ansibles/timezone
- https://github.com/Ansibles/ntp
- https://github.com/Ansibles/hostname
- https://github.com/Stouts/st.locale

#### Variables

```yaml
utilities_extras: # additional packages which be installed
    - curl
    - exuberant-ctags
    - git-flow
    - htop
    - mercurial
    - python-software-properties
    - screen
    - vim
    - wget
```

Also see documentation for required roles bellow.

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Stouts/Stouts.foundation/issues)!
