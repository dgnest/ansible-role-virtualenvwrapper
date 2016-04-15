# Ansible Role Virtualenwrapper

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-virtualenwrapper.svg)](https://travis-ci.org/hadenlabs/ansible-role-virtualenwrapper)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-virtualenwrapper.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-virtualenwrapper)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-virtualenwrapper.svg)](https://github.com/hadenlabs/ansible-role-virtualenwrapper/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [virtualenwrapper][link-virtualenwrapper] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for virtualenwrapper


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - virtualenwrapper

To install a specific version:

    - hosts: servers
      roles:
         - { role: hadenlabs.virtualenwrapper }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-luis]
- [All Contributors][link-contributors]


<!-- Other -->

[link-virtualenwrapper]: https://www.virtualenwrapper.com
[link-luis]: https://github.com/luismayta
[link-contributors]: contributors
