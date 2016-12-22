# Hadoop Ansible Playbook Example

## Requirements

* Ansible

## Security

Please change the following items.

* Hashed password in `group_vars/all` (default `kotamagoH@doop`)

## Servers

* Ubuntu 14.04

| IP Address     | Hostname  |                          |
|----------------|-----------|--------------------------|
| 192.168.11.101 | hadoop-01 | namenode, datanode, yarn |
| 192.168.11.102 | hadoop-02 | datanode, yarn           |
| 192.168.11.103 | hadoop-03 | datanode, yarn           |
| 192.168.11.104 | hadoop-04 | datanode, yarn           |
| 192.168.11.105 | hadoop-05 | datanode, yarn           |
| 192.168.11.106 | hadoop-06 | datanode, yarn           |
