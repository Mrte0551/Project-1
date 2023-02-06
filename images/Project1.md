## My Project 1 Documentation

`sudo apt update`

`sudo apt install apache2`

`sudo systemctl status apache2`

![Apache status](.//Apache%20Status.png)

![Apache HTTP server test](./Apache%20HTTP%20server%20Test.png)
`$ sudo apt install mysql-server`

`$ sudo mysql`

![My SQL installation](./My%20SQL%20test.png)

`ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'PassWord.1';`

`mysql> exit`

`$ sudo mysql_secure_installation`

`$ sudo mysql -p`

` mysql> exit`

`php -v`

`sudo mkdir /var/www/projectlamp`

` sudo chown -R $USER:$USER /var/www/projectlamp`

`sudo vi /etc/apache2/sites-available/projectlamp.conf`

`000-default.conf  default-ssl.conf  projectlamp.conf`

`sudo a2ensite projectlamp`

`sudo a2dissite 000-default`

`sudo apache2ctl configtest`

`sudo systemctl reload apache2`

`sudo echo 'Hello LAMP from hostname' $(curl -s http://169.254.169.254/latest/meta-data/public-hostname) 'with public IP' $(curl -s http://169.254.169.254/latest/meta-data/public-ipv4) > /var/www/projectlamp/index.html`

`sudo vim /etc/apache2/mods-enabled/dir.conf`

`sudo systemctl reload apache2`

`vim /var/www/projectlamp/index.php`
g
![enable php on website](./PHP%20ENABLED%20ON%20WEBSITE.png)