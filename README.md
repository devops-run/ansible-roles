# Репозиторий ролей Ansible 
---
### 1. Install Clickhouse DB role:   
- src: https://github.com/devops-run/ansible-roles/tree/main/clickhouse     

#### ansible-galaxy install -r requirements.yml -p roles

#### requirements.yml   

```yaml
---
- name: clickhouse
  src: git@github.com:devops-run/ansible-roles.git
  scm: git
  version: main
  name: clickhouse
```
### 2. Install Vector role:   
- src: https://github.com/devops-run/ansible-roles/tree/main/vector     

```yaml
- name: vector
  src: git@github.com:devops-run/ansible-roles.git
  scm: git
  version: main
  name: vector
```
