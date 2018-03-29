# WORDPRESS-MYSQL
Docker imagen servidor web Wordpress conectada a la base de datos mysql.

# USAGE
docker run -d --name wordpress-mysql -p 80:80/tcp javi98/wordpress-mysq

# MYSQL credentials
name database:      wordpress
user database:      wordpress
password database:  dbpassword
host database:      localhost
charset database:    utf8
