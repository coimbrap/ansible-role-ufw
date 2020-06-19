## Ansible role - UFW

### host_vars
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

Forked by Elukerio admins
