# launch-awx

This is Ansible playbook to launch AWX using docker and docker-compose on your server.

## Requirements

- python 2.7
- pip

## Usage

1. Launch AWX on your server

```
$ ansible-playbook awx.yml
```

2. Open port 80 on your server

3. Open http://[ip]:80 with browser
