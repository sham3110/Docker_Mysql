docker build -t mysql-image .

docker run --name mysql-instance -d -p 3306:3306 mysql-image

docker run --name mysql-instance -e MYSQL_ROOT_PASSWORD=**** -d -p 3306:3306 mysql
