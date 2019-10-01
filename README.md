# ansible-docker
Ansible docker playbook

## Usage

`docker.yaml`:

```
- name: install docker
  hosts: all
  roles:
    - ansible-docker
```

`hosts`:

```
[all]
10.2.0.100
```

Exec playbook:

```
ansible-playbook docker.yaml -i hosts --user root
```
