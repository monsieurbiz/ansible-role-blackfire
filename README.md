# Ansible Blackfire Role

It is not a nightmare to install blackfire but we prefer it that way.

## Requirements

* Ansible version 2.*

# Role Variables

You can override all the variables in `defaults/main.yml` in tour own vars.

# Dependencies

- [monsieurbiz.webserver](https://github.com/monsieurbiz/ansible-role-webserver)

## Example Playbook

    - hosts: servers
      roles:
         - { role: monsieurbiz.blackfire }

## License

MIT

## Authors

* Jacques Bodin-Hullin - [@jacquesbh](https://twitter.com/jacquesbh)

