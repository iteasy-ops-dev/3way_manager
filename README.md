Ansible Role: 3way Manager
=========

- 3way를 전문으로 관리합니다.

Requirements
------------
None.

Role Variables
--------------
- `defaults/main.yml` 참조
```yaml
user_id: ""
user_pass: ""
cband_limit: ""
disk_quota: ""
vhost_domain: ""
listen_port: ""

mysql_root_user: ""
mysql_root_password: ""
db_user: ""
db_name: ""
db_password: ""

setup: true
```

Dependencies
------------
Unknown.

Example Playbook
----------------
- `test/` 참조
```yaml
- hosts: vms
  remote_user: root
  roles:
    - ansible.roles.3way_manager
```

License
------------
BSD


해야 할것.
타 서버에서 디비 작업 확인 및 다른 것이 있는지 확인.
타 서버 테스트
배포
프론트 개발