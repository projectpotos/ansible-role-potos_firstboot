
# Ansible Role - potos\_firstboot

Role to run handle firstboot questions in Potos Linux Clients.

[![Test](https://github.com/projectpotos/ansible-role-potos_firstboot/actions/workflows/test.yml/badge.svg)](https://github.com/projectpotos/ansible-role-potos_firstboot/actions/workflows/test.yml)

## Example Playbook

As this role is tested via Molecule one can use [that
playbook](./molecule/default/converge.yml) as a starting point:

```yaml
---

- name: Converge
  hosts: all
  gather_facts: yes
  tasks:
    - name: run role
      ansible.builtin.include_role:
        name: 'ansible-role-potos_firstboot'
```

## Role Variables

The default variables are defined in [defaults/main.yml](./defaults/main.yml):

```yaml
---


```

Another option is to use `ansible-doc` to read the argument specification:

```sh
ansible-doc --type role -r . main ansible-role-potos_firstboot
```

## Requirements

N/A

## License

See [LICENSE](./LICENSE)

## Author Information

[Project Potos](https://github.com/projectpotos)

