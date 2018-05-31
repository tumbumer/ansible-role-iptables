# tumbumer.iptables

Firewall configuration

## Requirements

None.

## Role variables (optional)

var | choices | description
---|---|---
tumbumer_iptables_action | setup, update | Role action
tumbumer_iptables_forward | fasle, true | Enable network forwarding

## Dependencies

None.

## Example Playbook

```yaml
---
- hosts: all
  vars:
  - tumbumer_iptables_action: setup
  - tumbumer_iptables_forward: true
  roles:
  - tumbumer.iptables
```

## License

Apache-2.0

## Author Information

Denis Dvoretskov aka tumbumer <denis@tumbum.com>
