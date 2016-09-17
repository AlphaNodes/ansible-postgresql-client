# Ansible Role: PostgreSQL-Client

Installs PostgreSQL client on Debian and Ubuntu servers.

## Dependencies

  none

## Example Playbook

    - hosts: db-client
      vars:
        postgresql_client_use_repo: yes
      roles:
        - AlphaNodes.postgresql-client

## License

GPL Version 3

## Author Information

This role was created in 2016 by [Alexander Meindl](https://alphanodes.com/).
