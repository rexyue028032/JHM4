# JHM4

sudo apt-get update
sudo apt-get install -y mysql-server
sudo service mysql start
sudo mysql

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'Test-1234';