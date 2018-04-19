# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

| Change Type   | Description                            |
| :------------ | :------------------------------------- |
| Added         | for new features.                      |
| Changed       | for changes in existing functionality. |
| Deprecated    | for soon-to-be removed features.       |
| Removed       | for now removed features.              |
| Fixed         | for any bug fixes.                     |
| Security      | in case of vulnerabilities.            |

## [Unreleased]

## [2.1.2] - 2018-04-19

### Changed

- Changed Ansible version for tests

## [2.1.1] - 2018-04-06

### Added

- ignore .pytest_cache directory

### Changed

- Vagrantfile now uses pip for ansible
- Vagrantfile upgrades testinfra version
- Changed molecule version in tox
- Changed docker-compose version in tox
- changed ansible version in tox

### Fixed

- lock pip docker package to less than 3.0.0
  [https://github.com/ansible/ansible/issues/35612](https://github.com/ansible/ansible/issues/35612)
- molecule boolean value for privileged mode

## [2.1.0] - 2018-01-18

### Added

- tox testing

## [2.0.0] - 2017-12-08

### Added

- Vagrant private_network with dhcp
- Vagrant mount options to support macs and executable files
- Molecule for testing

### Changed

- changed Vagrant synced_folder to `/example-ansible-role/`
- changed role name to be more software agnostic

### Removed

- Dockerfiles from old test framework
- Makefile
- Debian 8 support

## [1.0.3] - 2017-11-13

### Added

- Added Changelog

### Changed

- Updated Readme with Ansible version requirement
- Renamed license file

[Unreleased]: https://github.com/joshuacherry/example-ansible-role/compare/2.1.2...HEAD
[2.1.2]: https://github.com/joshuacherry/example-ansible-role/compare/2.1.1...2.1.2
[2.1.1]: https://github.com/joshuacherry/example-ansible-role/compare/2.1.0...2.1.1
[2.1.0]: https://github.com/joshuacherry/example-ansible-role/compare/2.0.0...2.1.0
[2.0.0]: https://github.com/joshuacherry/example-ansible-role/compare/1.0.3...2.0.0
[1.0.3]: https://github.com/joshuacherry/example-ansible-role/compare/1.0.2...1.0.3