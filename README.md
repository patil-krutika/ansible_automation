# ansible_automation
---
- name: install httpd
  hosts: localhost
  tasks:
    - name: install webserver
      dnf:
        name: httpd
        state: latest
