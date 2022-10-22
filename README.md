# ansi-playbook-webserver-centos7
Installing Webserver on Centos 7 using Ansible AWX Tower

This Playbook works:
- Disabled SELinux
- Stop and disable firewalld
- Install Repository epel-release yum-utils remi-release
- Enable repo and install php7.4
- Install, Start, Enable HTTPD
- Install, Start, Enable MariaDB-Server
- Install memcached
- Install wget
- Install links
- Install cifs-utils
- Install nano
- Automatically create domain in HTTPD virtualhost config using Hostname target
