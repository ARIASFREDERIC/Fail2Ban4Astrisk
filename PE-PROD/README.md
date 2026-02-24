# Configuration of Fail2Ban for Asterisk

OS : Oracle Linux 8
Fail2ban : 
Asterisk : 

```bash
# fail2ban-server --version
Fail2Ban v1.0.2

```

# How to see the current list of IP ?

```bash
# fail2ban-client status asterisk
Status for the jail: asterisk
|- Filter
|  |- Currently failed: 7
|  |- Total failed:     7
|  `- File list:        /var/log/asterisk/full
`- Actions
   |- Currently banned: 2
   |- Total banned:     2
   `- Banned IP list:   111.111.111.111 37.140.254.90


```