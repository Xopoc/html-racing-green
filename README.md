html-racing-green
=================

Basic templates for Racing Green project.




Configuration and instalation
-----------------------------


### Apache vhost config ###

    <VirtualHost *:80>
        ServerName racing-green.zz
        DocumentRoot /racing-green/web
        <Directory /racing-green/web>
            # enable the .htaccess rewrites
            AllowOverride All
            Require all granted
        </Directory>
    </VirtualHost>
    

### Install  [Composer](https://getcomposer.org/ "composer")  ###
  Then run the following composer command:
  
    $ php composer.phar install
