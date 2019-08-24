# emcee
Master of Ceremonies - add and remove entries in your /etc/hosts file

## Install

```bash
$ curl -Lo- git.io/emcee-install | bash
```

## Commands

| Command | Action |
|---|---|
| `emcee add <hostname>` | Adds `<hostname>` with IP `127.0.0.1` to `/etc/hosts` |
| `emcee add <hostname> <ip>` | Adds `<hostname>` with IP `<ip>` to `/etc/hosts` |
| `emcee remove <hostname>` | Removes `<hostname>` from `/etc/hosts` |
| `emcee show <hostname>` | Shows the current line for `<hostname>` in `/etc/hosts` |
