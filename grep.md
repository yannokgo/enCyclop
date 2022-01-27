## Get the OS name with grep
```bash
cat /etc/os-release | grep ^NAME | grep -oP '"\K[^"\047]+(?=["\047])'
```
