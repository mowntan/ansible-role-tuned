# Ansible Role: tuned
| A role to install and configure tuned.

## Installation

Galaxy Link: <https://galaxy.ansible.com/while-true-do/tuned>

```
ansible-galaxy install while-true-do.tuned
```

Github Link: <https://github.com/while-true-do/ansible-role-tuned>

```
git clone https://github.com/while-true-do/ansible-role-tuned while-true-do.tuned
```

## Requirements

None.

## Dependencies

None.

## Role Variables

```
# defaults/main.yml
tuned_profile: balanced
```

## Example Playbook

Simple Example:

```
- hosts: servers
  roles:
    - { role: while-true-do.tuned }
```

Advanced Example:

```
- hosts: servers
  roles:
    - { role: while-true-do.tuned, tuned_profile: virtual-guest }
```

## License

This work is licensed under a [BSD License](https://opensource.org/licenses/BSD-3-Clause).

## Contribute / Bugs

**bug reports:** <https://github.com/while-true-do/ansible-role-tuned/issues>

**contributers:** <https://github.com/while-true-do/ansible-role-tuned/graphs/contributors>

## Author Information

**blog:** <https://blog.while-true-do.org>

**github:** <https://github.com/daniel-wtd>

**contact:** [mail@while-true-do.org](mailto:mail@while-true-do.org)
