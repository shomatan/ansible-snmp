# Ansible role: snmp

## Requirements
None.

## Role Variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|snmp_com2sec|Array||- { sec_name: public, source: default, community: public }|
|snmp_groups|Array||- { group_name: public_group, sec_name: public }|
|snmp_syslocation|String||Unknown|
|snmp_syscontact|String||Root <root@localhost>|
|snmp_dontLogTCPWrappersConnects|String||yes|

## Dependencies
None.

## Example playbook

```yaml
- hosts: all
  roles:
    - role: snmp
  vars:

```
