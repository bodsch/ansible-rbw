
# Ansible Role:  `rbw`

Ansible role to install and configure vaultwarden [cli tool](https://github.com/doy/rbw) on various linux systems.

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/bodsch/ansible-rbw/main.yml?branch=main)][ci]
[![GitHub issues](https://img.shields.io/github/issues/bodsch/ansible-rbw)][issues]
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/bodsch/ansible-rbw)][releases]
[![Ansible Downloads](https://img.shields.io/ansible/role/d/bodsch/vaultwarden?logo=ansible)][galaxy]

[ci]: https://github.com/bodsch/ansible-rbw/actions
[issues]: https://github.com/bodsch/ansible-rbw/issues?q=is%3Aopen+is%3Aissue
[releases]: https://github.com/bodsch/ansible-rbw/releases
[galaxy]: https://galaxy.ansible.com/ui/standalone/roles/bodsch/rbw/


## Requirements & Dependencies

Ansible Collections

- [bodsch.core](https://github.com/bodsch/ansible-collection-core)

```bash
ansible-galaxy collection install bodsch.core
```
or
```bash
ansible-galaxy collection install --requirements-file collections.yml
```

### Operating systems

Tested on

* Arch Linux
* Debian based
    - Debian 12

## configuration

```yaml

rbw_version: 1.10.1

rbw_state: present

```
## Contribution

Please read [Contribution](CONTRIBUTING.md)

## Development,  Branches (Git Tags)

The `master` Branch is my *Working Horse* includes the "latest, hot shit" and can be complete broken!

If you want to use something stable, please use a [Tagged Version](https://github.com/bodsch/ansible-rbw/tags)!


## Author

- Bodo Schulz

## License

[Apache](LICENSE)

**FREE SOFTWARE, HELL YEAH!**
