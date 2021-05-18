<a href="https://hadoop.apache.org/"><img src="images/Hadoop_logo.svg" width="100%" height="100%"></a>
# Ansible-Hadoop-Software-Setup-Role

An Ansible Role to Configure and setup software requirements for [Hadoop](https://hadoop.apache.org/) Cluster.

Requirements
------------
None

Role Variables
--------------
Available variables are listed below, along with default values (see vars/main.yml):
```
Java_Software_Directory: "/root/jdk_software/"
Java_Software_Version: "jdk-8u171-linux-x64.rpm"
Hadoop_Software_Directory: "/root/hadoop_software/"
Hadoop_Software_Version: "hadoop-1.2.1-1.x86_64.rpm"
```
Dependencies
------------
None

Example Playbook
----------------
```
 - hosts: all
   roles:
     - shubhambhardwaj007.hadoop_software_setup
```
License
-------

GNU

Author Information
------------------
This role was created in 2021 by [Shubham Bhardwaj](https://galaxy.ansible.com/shubhambhardwaj007/hadoop_software_setup)
