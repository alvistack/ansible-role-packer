# Ansible Role for Packer

## 5.1.0 - TBC

### Major Changes

  - Support openSUSE Leap 15.3

## 5.0.0 - 2021-06-02

### Major Changes

  - Install with official repo
  - Upgrade minimal Ansible support to 4.0.0
  - Support Fedora 34
  - Support Ubuntu 21.04
  - Install [Packer Plugin Docker](https://github.com/hashicorp/packer-plugin-docker)
  - Simplify download archive logic

## 4.7.0 - 2021-03-13

### Major Changes

  - Bugfix [ansible-lint `namespace`](https://github.com/ansible-community/ansible-lint/pull/1451)
  - Bugfix [ansible-lint `no-handler`](https://github.com/ansible-community/ansible-lint/pull/1402)
  - Bugfix [ansible-lint `unnamed-task`](https://github.com/ansible-community/ansible-lint/pull/1413)
  - Simplify Python dependency with system packages
  - Support RHEL 8 with Molecule
  - Support RHEL 7 with Molecule
  - Remove CentOS 8 support
  - Improve HTTP transparent proxy support
  - Improve download archive logic
  - Support CentOS 8 Stream
  - Support openSUSE Tumbleweed
  - Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

  - Simplify Molecule scenario for vagrant-libvirt
  - Migrate from Travis CI to GitLab CI
  - Support Fedora 33
  - Remove Fedora 32 support
  - Support Ubuntu 20.10

## 4.5.0 - 2020-10-21

  - Ininitial release for Ansible 2.10 or higher
  - This role was designed for:
      - Ubuntu 18.04/20.04
      - RHEL/CentOS 7/8
      - openSUSE Leap 15.2
      - Debian 10
      - Fedora 32
