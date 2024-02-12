# Throw away shell for LXC

- Add packages that are needed in the container via the script

```bash
check_and_install python3
check_and_install git
check_and_install perl
```

- You can also specify a specifc version if apk supports it

```bash
check_and_install <package> <version>
```
