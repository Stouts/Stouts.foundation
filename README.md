Stouts.foundation
=================

[![Build Status](http://img.shields.io/travis/Stouts/Stouts.foundation.svg?style=flat-square)](https://travis-ci.org/Stouts/Stouts.foundation)
[![Galaxy](http://img.shields.io/badge/galaxy-Stouts.foundation-blue.svg?style=flat-square)](https://galaxy.ansible.com/list#/roles/829)

Ansible role which contains the other common roles for setup new debian based machine

#### Installation

    $ ansible-galaxy install Stouts.foundation -p deploy/roles

#### Dependencies

- https://github.com/Ansibles/build-essential
- https://github.com/Ansibles/generic-users
- https://github.com/Ansibles/ntp
- https://github.com/Stouts/timezone
- https://github.com/Stouts/apt
- https://github.com/Stouts/hostname
- https://github.com/Stouts/Stouts.locale
- https://github.com/Stouts/Stouts.sudo

For manual installation:
'''
git submodule add https://github.com/Ansibles/build-essential deploy/roles/Ansibles.build-essential
git submodule add https://github.com/Ansibles/generic-users deploy/roles/Ansibles.generic-users
git submodule add https://github.com/Ansibles/ntp deploy/roles/Ansibles.ntp
git submodule add https://github.com/Stouts/Stouts.timezone deploy/roles/Stouts.timezone
git submodule add https://github.com/Stouts/Stouts.apt deploy/roles/Stouts.apt
git submodule add https://github.com/Stouts/Stouts.hostname deploy/roles/Stouts.hostname
git submodule add https://github.com/Stouts/Stouts.locale deploy/roles/Stouts.locale
git submodule add https://github.com/Stouts/Stouts.sudo deploy/roles/Stouts.sudo
'''

Also see documentation for required roles bellow.

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Stouts/Stouts.foundation/issues)!
