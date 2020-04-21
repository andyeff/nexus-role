# nexus-role

Ansible Role to install and configure Nexus Repository 3 OSS

Targeted for: Centos 7 / RHEL 7

Sample wrapper playbook to run role: https://github.com/andyeff/nexus-role-playbook

Tags to install:
- prereqs
- install
- config_core
- service

Tags to configure:
- config_app

Configuration is incomplete (generally just commented out) currently.

Forked from https://github.com/idealista/nexus-role

NOTE: Default config enables SSL, you will need an appropriate keystore.jks included in the files tree for a successful install
