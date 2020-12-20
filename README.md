## Ansible role - UFW

Ansible role to install and configure ufw

### Example

```yaml
ufw_rules:
- rule: allow
  interface: eth0
  to_port: 22,443
  protocol: tcp
```

#### License

GPLv3

#### Author Information

Mischa ter Smitten (based on work of weareinteractive)

Forked by Elukerio admins (Dan & Pierre Coimbra)
