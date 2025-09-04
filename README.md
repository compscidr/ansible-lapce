# ansible-lapce
[![Static Badge](https://img.shields.io/badge/Ansible_galaxy-Download-blue)](https://galaxy.ansible.com/ui/standalone/roles/compscidr/lapce/)
[![ansible lint](https://github.com/compscidr/ansible-lapce/actions/workflows/check.yml/badge.svg)](https://github.com/compscidr/ansible-lapce/actions/workflows/check.yml)
[![ansible lint rules](https://img.shields.io/badge/Ansible--lint-rules%20table-blue.svg)](https://ansible.readthedocs.io/projects/lint/rules/)

A simple role to install the Lapce IDE
https://github.com/lapce/lapce

## Testing

This role includes molecule tests to verify functionality. To run the tests locally:

```bash
# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install molecule molecule-docker

# Run molecule tests
molecule test
```
