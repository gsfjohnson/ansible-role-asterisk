# Ansible-Role-Asterisk

Install Asterisk

## Requirements

`gsfjohnson.repo-tucny`

## Variables

```yaml
asterisk_enablerepo: "asterisk-18"
asterisk_pkg_names: "asterisk asterisk-voicemail asterisk-pjsip"
asterisk_svc_state: started
```

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Examples

```yaml
    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
```

## License

MIT

## Author

gsfjohnson
