# Ansible role: XRay

This is ansible role for XRay.

# Development

## Setup

```bash
python3 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
```

## Run tests

```bash
cd xray
molecule test -s <scenario_name>
```

Scenarios: ubuntu2204.

# Links

- https://github.com/XTLS/Xray-core
- https://github.com/pilosus/Xray-ansible/tree/main
