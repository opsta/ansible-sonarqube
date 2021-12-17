# Ansible Role: SonarQube



## Requirements

must run host_preparation playbook with this vars 
```
host_preparation_sysctl_vars:
  - { regexp: '^vm\.max_map_count \= ', line: 'vm.max_map_count = 262144' }
```

## Role Variables

---
| sonarqube_version | input value   | remark         |
| :-                | :-            | :-----         | 
| 8.9.0             | 8.9.0.43852   |                |
| 8.9.1             | 8.9.1.44547   |                |
| 8.9.2             | 8.9.2.46101   |                |
| 8.9.3             | 8.9.3.48735   |                |
| 8.9.4             | 8.9.4.50575   |                |
| 8.9.5             | 8.9.5.50698   | LTS version    |
| 9.0.0             | 9.0.0.45539   |                |
| 9.0.1             | 9.0.1.46107   |                |
| 9.1.0             | 9.1.0.47736   |                |
| 9.2.0             | 9.2.0.49834   |                |
| 9.2.1             | 9.2.1.49989   |                |
| 9.2.2             | 9.2.1.50622   |                |
| 9.2.3             | 9.2.1.50713   |                |


## Dependencies



## Example Playbook

    - hosts: all
      roles:
        - ansible-sonarqube


## License

MIT

## Author Information

Opsta (Thailand) Co.,Ltd.
