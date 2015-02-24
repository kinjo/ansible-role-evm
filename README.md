ansible-role-evm
=========
 
An ansible role to install EVM [https://github.com/rejeep/evm](https://github.com/rejeep/evm)
 
Requirements
------------
 
Tested on Ubuntu 14.10 (Utopic Unicorn)
 
Role Variables
--------------
 
    # evm user (evm is installed its home directory)
    evm_user: "{{ ansible_ssh_user }}"

    # evm user's group
    evm_group: "{{ ansible_ssh_user }}"
 
Dependencies
------------
 
N/A
 
Example Playbook
----------------
 
    - hosts: local
      roles:
        - role: evm
      sudo: yes
 
License
-------
 
MIT
 
Author Information
------------------
 
[Takumi KINJO](http://github.com/kinjo/)
