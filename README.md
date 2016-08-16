#Script to Install

NPM
nodejs
mysql-server
httpd
remi
phpMyadmin

access ghost in /var/www/html/ghost

# curl --insecure https://raw.githubusercontent.com/Rahulsharma0810/Centos-Ghost-Deploy/master/ghost-install.sh | sh

Allow your Ip in /etc/httpd/conf.d/phpMyadmin.conf

Change mysql database-user & password in config.js --production under /var/www/html/ghost/config.js
