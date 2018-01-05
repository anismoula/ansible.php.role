# PHP 5 Ansible Role

Install PHP 5 for Debian/Ubuntu Linux Servers

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (/vars/main.yml) :

    php_conf_path               
    php_extension_conf_path
    php_packages  
    php_memory_limit            
    php_max_execution_time
    php_upload_max_filesize
    php_date_timezone

## Dependencies

None

## Example Playbook

    - hosts: servers
      become: yes
      roles:
        - ansible.role.php

## License

MIT

## Author Information

This role was created in 2018 by Moula Anis, System and Network Administrator.
