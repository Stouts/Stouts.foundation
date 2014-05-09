Stouts.foundation
=================

[![Build Status](https://travis-ci.org/Stouts/Stouts.foundation.png)](https://travis-ci.org/Stouts/Stouts.foundation)

Ansible role which contains the other common roles for setup new debian based machine

#### Requirements & Dependencies

- https://github.com/Ansibles/build-essential
- https://github.com/Ansibles/generic-users
- https://github.com/Ansibles/ntp
- https://github.com/Ansibles/timezone
- https://github.com/Stouts/apt
- https://github.com/Stouts/hostname
- https://github.com/Stouts/Stouts.locale
- https://github.com/Stouts/Stouts.sudo

'''
Git submodule add https://github.com/Ansibles/build-essential deploy/roles/Ansibles.build-essential
Git submodule add https://github.com/Ansibles/generic-users deploy/roles/Ansibles.generic-users
Git submodule add https://github.com/Ansibles/ntp deploy/roles/Ansibles.ntp
Git submodule add https://github.com/Ansibles/timezone deploy/roles/Ansibles.timezone
Git submodule add https://github.com/Stouts/hostname deploy/roles/Stouts.apt
Git submodule add https://github.com/Stouts/hostname deploy/roles/Stouts.hostname
Git submodule add https://github.com/Stouts/Stouts.locale deploy/roles/Stouts.locale
Git submodule add https://github.com/Stouts/Stouts.sudo deploy/roles/Stouts.sudo
'''

Also see documentation for required roles bellow.

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Stouts/Stouts.foundation/issues)!
