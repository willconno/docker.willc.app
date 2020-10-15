FROM mysql:5.7
MAINTAINER Will Connelly <connelly.william@gmail.com>
 
ENV MYSQL_USER=admin
ENV MYSQL_PASSWORD=root
ENV MYSQL_DATABASE=wordpress
ENV MYSQL_ROOT_PASSWORD=admin

COPY ./wordpress.sql /docker-entrypoint-initdb.d

EXPOSE  3306
