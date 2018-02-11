# Ansible role 'ansible-role-sudo'

An Ansible role for setting up sudo and sudo-rules.

## Requirements
This role ought to be fairly distro-agnostic as long as the package manager is supported by the package module.

## Role Variables
| Variable		| Default		| Comments (type) |
| :---			| :---			| :---		  |
| `sudo_wheel_all` | `nopass` | Allow users in group `wheel` to execute all with or without password (`pass` or `nopass`) |

## Dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: ansible-role-sudo
```

## Testing


## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
