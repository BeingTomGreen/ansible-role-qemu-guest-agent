# beingtomgreen.qemu_guest_agent

Simple Ansible role to ensure the `qemu-guest-agent` is present and enabled on QEMU based systems.

## Installation

Given that Galaxy seems to have abandoned roles, I suggest referencing this repository directly in your projects `requirements.yml`:

```yml
---

roles:
  - name: beingtomgreen.qemu_guest_agent
    src: https://github.com/BeingTomGreen/ansible-role-qemu-guest-agent.git

collections: []
```

You can then install the requirements as normal:

```bash
ansible-galaxy install -r requirements.yml
```

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yml
- hosts: vms
  become: true
  roles:
    - beingtomgreen.qemu_guest_agent
```

## License

[MIT](LICENSE)

## Author Information

[Tom Green](https://github.com/BeingTomGreen)
