# Ansible Role - Installing and configuring php-fpm

Installs and configures php fpm for a vhost.

#### Variables

* php_fpm_poolname: name of php fpm configuration file
* php_fpm_user: name of user to run the fpm process
* php_fpm_chdir: usually the htdocs directory
* php_fpm_tmpdir: usually a tmp dir for sessions
* php_ini_memory_limit: (default=512M)
* php_fpm_open_basedir: add additional open_basedir files/folders
