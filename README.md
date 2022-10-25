# Ansible Role to install nerdctl

Make changes to `ansible-role-nerdctl/defaults/main.yaml` to adjust for your system and environment. 

## Expectation
* Rootless containers
* Ubuntu 20.04 - No cgroup v2 as this is a kernel boot option.
* Ubuntu 22.04 - cgroup v2 enabled by default.

## Example install
```
ansible-playbook --limit 'target.hostname.net,' --ask-pass --ask-become-pass --become install.yaml
```


