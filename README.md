# Magento 2 Full Stack Development Server Build
Ubuntu Server 16.04 LTS (Xenial Xerus) - LAMP Full Stack Server Build
Build with most secure web server nginx, trusted database server percona mysql server with run dynamic php script php7.0-fpm.
Also enhance application performnace with most trusted cache servr as varnish and data key value store as redis server.
Application configured with built in Mail service with Postfix.

# commnad to Launch Container.
docker run -i -t -d --name web-server -e project_name=ktpl -e pma_user=pma -e dev_user=magento -e dev_password=magento123 -e root_password =root123 ktpl00/inhouse-sites-server
