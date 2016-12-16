Role Name
=========

Ansible role to install Oracle Java JDK and JCE 8

Requirements
------------

Ansible 2.2 must be installed in the host where the playbook will be executed.

Recommended install Ansible via pip (http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip)

Role Variables
--------------

- **jdk8_url**: URL to download Oracle Java JDK 8
- **jdk8_rpm_file** Linux RPM file name for Java
- **jdk8_unzipped_folder**: Name of the JCE folder when it is unzipped
- **jdk8_install_folder**: Name of the java installation folder
- **jce8_url**: URL to download JCE 8 zip file
- **jce8_file**: JCE Zip filename

Dependencies
------------

None

Example Playbook
----------------

main.yml playbook
```
    - hosts: localhost
      roles:
         - overdrive3000.java8 
```

License
-------

BSD

Author Information
------------------

Juan Mesa - linuxven@gmail.com
