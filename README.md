# SE Linux


## Files

- /etc/selinux/config
  
## Cmds

- `semanage fcontext -a -t public_content_t /etc/bogus`
- getenforce
- setenforce
- `restorecon -v /etc/bogus`
- fixfiles
- booleans
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

