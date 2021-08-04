# Ansible Role: VNC-Server

Installs VNC server software [TigerVNC](https://tigervnc.org/) for use with [LightDM](https://github.com/canonical/lightdm).

## Requirements

- Ansible 2.10+
- Debian-based linux-distribution

## Dependencies

None.

## Role Variables

```yaml
websockify_version: "1.0.1"
```

```yaml
vnc_port: 5901
```

```yaml
websockify_port: 7000
```

## Configuration example

```yaml
- name: Configure VNC
  hosts: clients
  roles:
    - vnc-server
```

## Licence

GPL-3.0

## Author information

Benjamin Akhras
