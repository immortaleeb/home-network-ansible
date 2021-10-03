# Home network setup

This contains a bunch of ansible playbooks that I use to setup and manage my home network.

## Excito B3

To setup a wiped disk, first run:

```
ansible-playbook -i hosts setup_b3.yml --user excito --ask-pass --ask-become-pass
```

The default user and password should be `excito`.

## Raspberry pi

To setup a fresh installation of raspberry pi os, run:

```
ansible-playbook -i hosts setup_raspberrypi.yml --user pi --ask-pass
```

The default password should be `raspberrypi`

