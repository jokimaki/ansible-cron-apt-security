# cron-apt-security

Configures automatic security update installation for Debian stable.

Configuration is based on <http://www.the-art-of-web.com/system/cron-apt-wheezy/> 
with a modification that always the latest stable is supported.

## Usage

Include this role in your ansible playbook, for example:

```yaml
---
- hosts: all
  roles:
    - cron-apt-security
```

## License

Copyright (c) 2015 Juha Jokimäki

Licensed under the MIT License:
<http://www.opensource.org/licenses/mit-license.php>

