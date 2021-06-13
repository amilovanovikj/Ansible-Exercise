# Ansible Exercise

This repository represents an exercise with Ansible playbooks and roles. It contains the following:
- Spin up 3 virtual machines using Vagrant
- Install Apache server using an Ansible playbook on "webserver" hosts.
- Serve a static HTML file that has been templated with Jinja2 on "webserver" hosts.
- Use for loops, if statements and Ansible variables in Jinja2 template.
- Install Java and Elasticsearch using Ansible roles on "database" hosts.
- Query Elasticsearch from "webserver" hosts.
- Load a secret from Ansible Vault and display its content.