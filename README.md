# Ansible role: git

Install git on RedHat/CentOS or Debian/Ubuntu distros.

[CHANGELOG](./CHANGELOG.md)

## Requirements

None.

## Role variables

Available variables are listed below, along with default values (see `default/main.yml`):

    git_repo: []

Minimal config:

    git_repo:
        - repo: https://github.com/some-repo
          dest: /some/directory
          version: main

For more options look at `Clone repository` task in `tasks/main.yml`.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - dragomirr.git

## License

GPLv3
