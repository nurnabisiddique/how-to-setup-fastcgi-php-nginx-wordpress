1. follow this tutorial first https://techglimpse.com/configure-nginx-php-fastcgi-centos/
2. instead of "sudo systemctl status php8.1-fpm" execute "sudo systemctl status php-fpm"

     - sudo systemctl enable php-fm
     - sudo systemctl enable php-fpm
     - sudo systemctl restart  php-fpm

some useful links
     - https://stackoverflow.com/questions/23640576/how-to-get-php-installation-path
     - https://www.linode.com/docs/guides/how-to-use-nginx-fastcgi-page-cache-with-wordpress/
