# SE Linux


## Files

- /etc/selinux/config
  
## Cmds

- [semanage](semanage.md)
- [sesearch](sesearch.md)
- getenforce
- setenforce
- `semodule -l`
- `seinfo -c`
- `restorecon -v /etc/bogus`
- fixfiles
- booleans
- chcon
- setsebool
- sepolicy
- system-config-selinux
- togglesebool
- setfiles
- sepolicy
- audit2allow
- semodule
- sealert


## Man

- man -k selinux
- man httpd_selinux

## RPMs

- selinux-policy-doc

## Misc

`egrep AVC /var/log/audit.log`

