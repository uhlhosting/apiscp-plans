# apiscp-plans
Change ApisCP plans

# Example playbook

```
- name: Play for modifying ApicCP plans
  hosts: test
  become: true
  gather_facts: true
  roles:
    - uhlhosting.apiscp_plans
```
