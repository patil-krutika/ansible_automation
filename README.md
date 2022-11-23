# ansible_automation
---
- name: install httpd
  hosts: 192.168.1.92
  tasks:
    - name: install webserver
      yum:
        name: httpd
        state: latest
