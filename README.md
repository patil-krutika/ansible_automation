# ansible_automation
---
- name: install httpd
  hosts: localhost
  tasks:
    - name: install webserver
      yum:
        name: httpd
        state: latest
