# Ansible-Role-Asterisk

Install Asterisk

## Requirements

None

## Variables

```yaml
asterisk_enablerepo: "asterisk-18"
asterisk_pkg_names: "asterisk asterisk-voicemail asterisk-pjsip"
asterisk_svc_state: started
```

## Dependencies

* Asterisk packages must be available in the repo.  e.g. gsfjohnson.repo-tucny

## Examples

```yaml
- hosts: voip
  roles:
    - role: gsfjohnson.repo-tucny
    - role: gsfjohnson.asterisk
```

## License

MIT

## Author

gsfjohnson
