# # CVE-2022-40684 
CVE-2022-40684 - Auth bypass extract admin users and LDAP config - This PoC do only read-only actions.

- Run exploit

```
USE: python3 exploit.py https://target.com
Ex: python3 exploit.py https://target.com

```

- Run nuclei template

```
echo https://target.com | nuclei -t CVE-2022-40684.yaml
```

