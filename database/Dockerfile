FROM mysql:8-oracle

ENV MYSQL_ROOT_PASSWORD=root

ENV MYSQL_USER=root

EXPOSE 3306

COPY database.sql /docker-entrypoint-initdb.d/database.sql