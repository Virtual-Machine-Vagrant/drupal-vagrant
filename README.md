# Drupal Vagrant

An Empty Linux Vagrant Machine to start a new project

# To use this

Just install vagrant and virtualbox in your machine, checkout this project, go to the root folder and run

 vagrant up
 
That will start the vagrant provisioning for a virtual machine with linux and all setted up to work in the src folder where we have a drupal 7 instalation.

## Properties
  
- Debian Based machine
- Shared folders via NFS
- Default IP : 10.11.12.119
- Default Shared : /var/www
- Mysql, user root, password empty
- Varnish by default
- Memcahced by default
- Drush 
- Compass /usr/bin/local/compass
- There is a clean dump in sql, you can import it in a database called drupal and use the current instalation
  - User admin, pass 123123

## Composer installation

If you need composer use this
 
``` 
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
```

