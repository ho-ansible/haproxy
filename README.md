# Ansible role: haproxy
Load balancer and reverse proxy.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `haproxy_ports`: list of TCP ports to open on firewall
+ `haproxy_frontends`: dict of config for each front end
+ `haproxy_backends`: dict of config for each back end
+ `haproxy_cfg`: extra custom config

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run prior to removing host from inventory group.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
