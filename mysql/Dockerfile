FROM mysql:5.7


ENV MYSQL_ROOT_PASSWORD=
ENV MYSQL_ALLOW_EMPTY_PASSWORD=true
ENV MYSQL_DATABASE=test

COPY init.sql /docker-entrypoint-initdb.d/


