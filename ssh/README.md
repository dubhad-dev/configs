# SSH Guide

## Server

Place file `sshd_config` to `/etc/ssh/sshd_config`

## Client

Place file `ssh_config` to `~/.ssh/config`

## Key generation

- `ssh-keygen -t ed25519 -f ~/.ssh/id_ed25519_my_key -C "Key description"` - preferred

- `ssh-keygen -t rsa -b 4096 -f ~/.ssh/id_rsa_my_key -C "Key description"` - for compatibility

## Reference

https://infosec.mozilla.org/guidelines/openssh
