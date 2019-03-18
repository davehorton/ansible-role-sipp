# ansible-role-sipp [![Build Status](https://secure.travis-ci.org/davehorton/ansible-role-drachtio.png)](http://travis-ci.org/davehorton/ansible-role-drachtio)

This is an ansible role for building [sipp](http://sipp.sourceforge.net). The playbook builds sipp with support for pcap play as well as rtp streaming.

## Role variables

Available variables are listed below, along with default values (see defaults/main.yml):

```
sippVersion: v3.1.5
```
The version of sipp to build.

## Example playbook
```
---
- hosts: all
  become: yes
  roles:
    - ansible-role-sipp
```
