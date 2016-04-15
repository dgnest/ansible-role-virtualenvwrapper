# Ansible Role Virtualenvwrapper

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-virtualenvwrapper.svg)](https://travis-ci.org/hadenlabs/ansible-role-virtualenvwrapper)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-virtualenvwrapper.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-virtualenvwrapper)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-virtualenvwrapper.svg)](https://github.com/hadenlabs/ansible-role-virtualenvwrapper/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [virtualenvwrapper][link-virtualenvwrapper] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for virtualenvwrapper


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - virtualenvwrapper

To install a specific version:

    - hosts: servers
      roles:
         - { role: hadenlabs.virtualenvwrapper }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-luis]
- [All Contributors][link-contributors]


<!-- Other -->

[link-virtualenvwrapper]: https://www.virtualenvwrapper.com
[link-luis]: https://github.com/luismayta
[link-contributors]: contributors
