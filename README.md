# Ansible Role: mirsg.install_python

This role will install and configure a PostgreSQL database on a server.

## Requirements

If you would like to run Ansible Molecule to test this role, the requirements are in [`requirements.txt`](https://github.com/UCL-MIRSG/ansible-role-postgresql/blob/main/requirements.txt).

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook

### Basic usage

Create and setup a PostgreSQL database on a server called `server`:

    - hosts: server
      roles:
         - { role: mirsg.postgresql}

### Passing variables

You can set variables in the playbook as followes:

    - hosts: server
      roles:
         - { role: mirsg.postgresql, disable_postgres_rpm_gpg_check: "true" }

## License

[BSD 3-Clause License](https://github.com/UCL-MIRSG/ansible-role-postgresql/blob/main/LICENSE).

## Author Information

This role was created by the [Medical Imaging Research Software Group](https://www.ucl.ac.uk/advanced-research-computing/expertise/research-software-development/medical-imaging-research-software-group) at [UCL](https://www.ucl.ac.uk/).
