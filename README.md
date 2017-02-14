# gitlab-centos

GitLab CE Install
=================

This role install GitLab CE on a CentOS/RHEL 7 server. 

Requirements
------------

You will need to have internet access on the target server in order to be able to get and install the required packages. 

Dependencies
------------

There is no role dependency for this role.

Host File
----------

The host file for this role is hosts.target and the format is:

[gitlab-server]
IP FOR GITLAB SERVER

How to run the playbook
------------------------

**  Change the host target IP on the hosts.target inventory file to point to the server that you want to deploy.

** Run the playbook

ansible-playbook -i hosts.target gitlab-ce.yml

License
-------

Apache

Author Information
------------------

Julio Villarreal Pelegrino <julio@linux.com> more at: http://wwww.juliovillarreal.com & http://www.juliosblog.com
